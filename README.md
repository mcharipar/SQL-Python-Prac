# SQL-Python-Prac
Some python files working with SQL and data cleaning

## [sqlDataModeling.ipynb](sqlDataModeling.ipynb)
### Quick Overview
[See PDF File.](sqlDataModeling.pdf)
### Installation
- Must have [Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.

### Linux
- Navigate to project folder and paste this command in the terminal.
```
source installation.txt
```
### MacOS
- Navigate to project folder and paste this command in the terminal.

Paste contents of [`installation.txt`](installation.txt) in a terminal.

## Windows
- Navigate to project folder and paste this command in an anaconda command prompt.
```
installation.bat
```
- Must have [PostgreSQL installed](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads) 

- Update the [`.env`](.env) file to load PostegreSQL password into the notebook. 
    - Not considered *best practice*, but can hard code PostegreSQL within notebook.

## [More_Act](More_Act)
Contains 2 notebook file:
- [dataHandoff.ipynb](More_Act/dataHandoff.ipynb)
- [jsonInterpreter.ipynb](More_Act/jsonInterpreter.ipynb)
### Installation
Same instructions as above except use [More_Act/installation_fresh.bat](More_Act/installation_fresh.bat) or [More_Act/installation_fresh.txt](More_Act/installation_fresh.txt)