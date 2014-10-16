# BIOMD0000000144: Model_generated_by_BIOCHAM

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000144.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000144.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000144 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the Dynamical model of nuclear division cycles during early
embryogenesis of Drosophila, without StringT regulation. so ksstg=kdstg=0.
Figure1B has been simulated by MathSBML. Curator changed model from only one
compartment into two compartments according to the paper. Detail explaination
of the models are in the supplement information of the paper.The author didn't
specify which compartment Xm, Stgm, Xp are located, we assume that they locate
in cytoplasm.

Some of the parameter values for the equations are dimensionless parameters.

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


