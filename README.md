# MODEL1002160000: GomezCabrero2011_Atherogenesis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1002160000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1002160000.git@20140916`

## Usage

Importing the model package.

`import MODEL1002160000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**Workflow for generating competing hypothesis from models with parameter uncertainty.**   
David Gomez-Cabrero, Albert Compte and Jesper Tegner _Interface Focus_ 6 June
2011 vol. 1 no. 3 438-449; doi:
[10.1098/rsfs.2011.0015](http://dx.doi.org/10.1098/rsfs.2011.0015)  
**Abstract:**   
Mathematical models are increasingly used in life sciences. However, contrary
to other disciplines, biological models are typically over-parametrized and
loosely constrained by scarce experimental data and prior knowledge. Recent
efforts on analysis of complex models have focused on isolated aspects without
considering an integrated approach-ranging from model building to derivation
of predictive experiments and refutation or validation of robust model
behaviours. Here, we develop such an integrative workflow, a sequence of
actions expanding upon current efforts with the purpose of setting the stage
for a methodology facilitating an extraction of core behaviours and competing
mechanistic hypothesis residing within underdetermined models. To this end, we
make use of optimization search algorithms, statistical (machine-learning)
classification techniques and cluster-based analysis of the state variables'
dynamics and their corresponding parameter sets. We apply the workflow to a
mathematical model of fat accumulation in the arterial wall (atherogenesis), a
complex phenomena with limited quantitative understanding, thus leading to a
model plagued with inherent uncertainty. We find that the mathematical
atherogenesis model can still be understood in terms of a few key behaviours
despite the large number of parameters. This result enabled us to derive
distinct mechanistic predictions from the model despite the lack of confidence
in the model parameters. We conclude that building integrative workflows
enable investigators to embrace modelling of complex biological processes
despite uncertainty in parameters.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/).  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


