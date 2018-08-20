# Introduction to Bayesian statistical modelling with PyMC3

## Description

This repository contains a series of notebooks to get hands-on experience applying practical Bayesian statistical modeling methods with PyMC3.

The beauty of Bayesian statistical modelling is that it is principled. It can be applied generally to a wide variety of problems, from modelling a distribution to generalized linear model with random effects. Moreover, the benefit from the _Bayesian approach come not from default implementations, valuable as they can be in practice, but in the active process of model building, checking, and improvement. [...] Under a Bayesian approach, all the tuning parameters are supposed to be interpretable in real-world terms, which implies—or should imply—that improvements in a Bayesian model come from, or supply, improvements in understanding of the underlying problem under studied._ [[ref]](https://www.kdnuggets.com/2016/12/bayesian-basics-explained.html)

If you prefer not to install the software requirements, you can play around with the notebooks on Binder: 
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/JackCaster/Intro_to_PyMC3/master). Note, it may take 10/15 min to launch.

## Software requirements

The notebooks are supposed to be run with Python 3.6. I recommend installing the [Miniconda](https://www.continuum.io/downloads) distribution of Python 3, as it allows for the easy automation of package installation and virtual environment creation (see instructions below).

## Getting the materials

Clone this repository into a directory of your choice.

    git clone https://github.com/JackCaster/Intro_to_PyMC3.git

If you are not familiar with Git and GitHub, you can simply download the zip file of the repository at the top of the main repository page.

Then, move to the directory created by the clone/zip file:

    cd Intro_to_PyMC3

and install everything using `conda`:

    conda env create -f environment_windows.yml     # if on Windows 64
    conda env create -f environment.yml             # if on Mac
    
This will create an environment called `intro_to_pymc3` that includes the packages required for the tutorial.    

To use the environment, you need to activate it by typing:

    activate intro_to_pymc3        # Windows
    source activate intro_to_pymc3 # Mac

Finally, fire up jupyter notebook by typing:

    jupyter notebook
