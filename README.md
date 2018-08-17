# Introduction to Bayesian statistical modelling with PyMC3

Alberto Morando
Chalmers University of Technology

## Description

This is a beginner-level tutorial to get hands-on experience applying practical Bayesian statistical modeling methods on real data.

THe beauty of Bayesian statistical modelling is that it is principled. It can be applied generally to a wide variety of problems, from modelling a distribution to generalized linear model with random effects.

## Outline

1. Introduction

## Software requirements

This tutorial assumes that you are using Python 3.6. I recommend installing the [Miniconda](https://www.continuum.io/downloads) distribution of Python 3, as it allows for the easy automation of package installation and virtual environment creation (see instructions below).

## Getting the tutorial materials

Clone this repository into a directory of your choice.

    git clone https://github.com/JackCaster/Intro_to_PyMC3.git

If you are not familiar with Git and GitHub, you can simply download the zip file of the repository at the top of the main repository page.

Then, move to the directory created by the clone/zip file:

    cd Intro_to_PyMC3

and install everything using `conda`:

    conda env create -f environment_WIN.yml     # if on Windows 64
    conda env create -f environment_MAC_OSX.yml # if on Mac
    
This will create an environment called `intro_to_pymc3` that includes the packages required for the tutorial.    

To use the environment, you need to activate it by typing:

    activate intro_to_pymc3        # Windows
    source activate intro_to_pymc3 # Mac
