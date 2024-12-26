# info-2950-project

An analysis of class income on certain economic indicators. Data was
downloaded from
<https://databank.worldbank.org/source/world-development-indicators#> on
10/20/24. More information about the data can be found in the Jupyter Notebook.

## Conda Environment Setup

The Python environment was created using **Anaconda 2.6.2**
and creating an environment within the Anaconda Navigator
with **Python 3.12**. The following packages were installed
in the environment:

- `jupyter`
- `pandas`
- `seaborn`
- `duckdb` (using `conda install -c conda-forge python-duckdb`)

Packages can also be installed using
```conda install requirements.txt```.

## Usage

1. Set up a Conda Environment installing the packages
2. outlined in [this reference](#conda-environment-setup).
3. Run the Jupyter Notebook in the created Kernel.

## Sources

[Git Ignores for Jupyter Notebook Projects](https://medium.com/@cruble/a-quick-guide-for-making-a-git-ignore-gitignore-e645d70676b2)

- used to find out how to construct `.gitignore` for Jupyter Notebook

<https://databank.worldbank.org/source/world-development-indicators#>

- downloaded dataset from here
