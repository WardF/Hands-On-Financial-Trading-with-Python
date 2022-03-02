# Cheatsheet for commands/conda

## Bookmarks

* [https://towardsdatascience.com/how-to-set-up-anaconda-and-jupyter-notebook-the-right-way-de3b7623ea4a](https://towardsdatascience.com/how-to-set-up-anaconda-and-jupyter-notebook-the-right-way-de3b7623ea4a)

## Environmental Commands

Set up the environment using the following (jupyter notebook):

    $ conda install -c conda-forge notebook nb_conda_kernels matplotlib numpy pandas scipy seaborn dtale mpld3

Alternatively, set up the environment using `jupyterlab`

    $ conda install -c conda-forge jupyterlab nb_conda_kernels matplotlib numpy pandas scipy seaborn dtale mpld3  


## General Conda commands

* `conda env list`
* `conda create -n [quantfi]`
* `conda activate [quantfi]`
* `conda env update --file environment.yml`

