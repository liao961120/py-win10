Snakemake Dependencies on Windows
=================================

This repo (GitHub Action) was set up to build `Python 3.11`-related binaries for Snakemake dependencies on Windows 10/11. 
The built dependencies are available on the `gh-pages` branch. 
Download and extract the contents in `py311.zip` and copy them into your local python library (site-packages) path.
This makes available the snakemake dependencies on your local computer.

Next, you have to run

```
pip install snakemake
```

and then 

```
pip uninstall snakemake
```

and, finally,

```
pip install snakemake==8.14.0
```

to make the `snakemake` command available through the command line.
