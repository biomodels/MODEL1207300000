# MODEL1207300000: Watterson2012_CholesterolBiosynthesisPathway

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1207300000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1207300000.git@20140916`

## Usage

Importing the model package.

`import MODEL1207300000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**A model of flux regulation in the cholesterol biosynthesis pathway: Immune mediated graduated flux reduction versus statin-like led stepped flux reduction.**   
Watterson S, Guerriero ML, Blanc M, Mazein A, Loewe L, Robertson KA, Gibbs H,
Shui G, Wenk MR, Hillston J, Ghazal P. _Biochimie._ 2012 Jun 1.
[22664637](http://www.ncbi.nlm.nih.gov/pubmed/22664637) ,  
**Abstract:**   
The cholesterol biosynthesis pathway has recently been shown to play an
important role in the innate immune response to viral infection with host
protection occurring through a coordinate down regulation of the enzymes
catalysing each metabolic step. In contrast, statin based drugs, which form
the principle pharmaceutical agents for decreasing the activity of this
pathway, target a single enzyme. Here, we build an ordinary differential
equation model of the cholesterol biosynthesis pathway in order to investigate
how the two regulatory strategies impact upon the behaviour of the pathway. We
employ a modest set of assumptions: that the pathway operates away from
saturation, that each metabolite is involved in multiple cellular interactions
and that mRNA levels reflect enzyme concentrations. Using data taken from
primary bone marrow derived macrophage cells infected with murine
cytomegalovirus or treated with IFNγ, we show that, under these assumptions,
coordinate down-regulation of enzyme activity imparts a graduated reduction in
flux along the pathway. In contrast, modelling a statin-like treatment that
achieves the same degree of down-regulation in cholesterol production, we show
that this delivers a step change in flux along the pathway. The graduated
reduction mediated by physiological coordinate regulation of multiple enzymes
supports a mechanism that allows a greater level of specificity, altering
cholesterol levels with less impact upon interactions branching from the
pathway, than pharmacological step reductions. We argue that coordinate
regulation is likely to show a long-term evolutionary advantage over single
enzyme regulation. Finally, the results from our models have implications for
future pharmaceutical therapies intended to target cholesterol production with
greater specificity and fewer off target effects, suggesting that this can be
achieved by mimicking the coordinated down-regulation observed in
immunological responses.


