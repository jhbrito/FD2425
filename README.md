# FD2425

MEEC FD 2024/2025

## Create conda environment
conda create -n FD2425Env310 -python=3.xx

or

conda create -p PATH python=3.10

## Export conda environment
conda env export > environment.yml

## Import conda environment
conda env create -n Project_Environment_Name --file environment.yml

## Import pip environment
pip install -r requirements.txt

## Export pip environment
pip freeze > requirements.txt

## Unofficial Windows Binaries for Python Extension Packages
<https://www.lfd.uci.edu/~gohlke/pythonlibs/>