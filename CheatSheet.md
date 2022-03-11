# Cheatsheet for commands/conda

## Bookmarks

* [https://towardsdatascience.com/how-to-set-up-anaconda-and-jupyter-notebook-the-right-way-de3b7623ea4a](https://towardsdatascience.com/how-to-set-up-anaconda-and-jupyter-notebook-the-right-way-de3b7623ea4a)

## General Conda commands

### List and create environments

* `conda env list`
* `conda create -n [quantfi]`
* `conda activate [quantfi]`

Updating all the packages in an environment:

* `conda update -n [environment] --all`


### Bootstrap environments for this project

Set up the environment using the following (jupyter notebook):

    $ conda install -c conda-forge notebook nb_conda_kernels matplotlib numpy pandas scipy seaborn dtale mpld3

Alternatively, set up the environment using `jupyterlab`

    $ conda install -c conda-forge jupyterlab nb_conda_kernels matplotlib numpy pandas scipy seaborn dtale mpld3  

### Jupyter Lab/Notebook

    $ jupyter lab

*or*

    $ jupyter notebook