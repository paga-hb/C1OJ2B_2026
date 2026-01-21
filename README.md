# Object-Oriented Software Development (C1OJ2B) Spring 2026
This is the repository for the Object-Oriented Software Development (Spring 2026) course at Borås University.

The course schedule can be found on [Kronox](https://schema.hb.se/setup/jsp/Schema.jsp?startDatum=2026-01-20&intervallTyp=m&intervallAntal=1&sprak=SV&sokMedAND=true&forklaringar=true&resurser=k.C1OJ2B-20261-I13V6-) and the course material can be found on [Canvas](https://hb.instructure.com/courses/11167).

## Delopment Environment Setup

First, make sure you have installed Visual Studio Code, Miniconda, Git, and the .NET Sdk on your computer.

### Software

Install the following software on your computer:

  -  [Visual Studio Code](https://code.visualstudio.com)
  -  [Miniconda](https://docs.anaconda.com/miniconda/install/#quick-command-line-install)
  -  [Git](https://git-scm.com/downloads)
  -  [.NET Sdk](https://dotnet.microsoft.com/en-us/download) (install .net 10.0)

### Verify the Software Installation
Verify the software has been successfully installed, by opening a terminal and issuing the following commands (each command should print out a version):

  - `code --version`
  - `conda --version`
  - `git --version`
  - `dotnet --version`

If you don't see the print-out of a version for a specific tool, make sure the path to your tool has been added to your `PATH` environment variable. Also, run the command below to verify you have installed. at least. .net sdk version 10.0.

- `dotnet --list-sdks`

## Course Repository

When you have installed the software above, open a terminal and clone the GitHub repository [C1OJ2B_2026](https://github.com/paga-hb/C1OJ2B_2026.git) to your computer, and create a Python environment:

- `git clone https://github.com/paga-hb/C1OJ2B_2026.git testing`
- `cd testing`
- `conda create -y -p ./.conda python=3.12`
- `conda activate ./.conda`
- `python -m pip install --upgrade pip`
- `pip install ipykernel jupyter`

## Visual Studio Code (VSCode) Extensions

Then install the necessary Visual Studio Code Extensions by executing the commands below in your terminal:

- `code --install-extension ms-dotnettools.csdevkit --force`
- `code --install-extension ms-dotnettools.vscodeintellicode-csharp --force`
- `code --install-extension ms-toolsai.jupyter --force`
- `code --install-extension yzhang.markdown-all-in-one --force`
- `code --install-extension ms-python.python --force`
- `code --install-extension humao.rest-client --force`
- `code --install-extension ms-mssql.mssql --force`
- `code --install-extension alexcvzz.vscode-sqlite --force`

## Open the First Workshop Notebook

Finally, make sure you are in the `testing` folder in your terminal, and open the first notebook in Visual Studio Code, by issuing the command below:

- `code -g notebooks/vscode1.ipynb:0 .`

When the notebook opens in VSCode, click the text `Select Kernel` (in the top-right of the notebook), and choose `Python Environments... => conda (Python 3.12) .conda/bin/python`.

Now you can follow the instructions in the notebook.
