# BIOMD0000000266: voit03

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000266.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000266.git@20140916`


# Model Notes


This is the S systems model described in the article:  
**Biochemical and genomic regulation of the trehalose cycle in yeast: review of observations and canonical model analysis**   
_Eberhard O Voit, J Theor Biol 2003 223:55-78_ PubmedID:
[12782117](http://www.ncbi.nlm.nih.gov/pubmed/12782117) ; DOI:
[10.1016/S0022-5193(03)00072-9](dx.doi.org/10.1016/S0022-5193\(03\)00072-9)  
Abstract:  
The physiological hallmark of heat-shock response in yeast is a rapid,
enormous increase in the concentration of trehalose. Normally found in growing
yeast cells and other organisms only as traces, trehalose becomes a crucial
protector of proteins and membranes against a variety of stresses, including
heat, cold, starvation, desiccation, osmotic or oxidative stress, and exposure
to toxicants. Trehalose is produced from glucose 6-phosphate and uridine
diphosphate glucose in a two-step process, and recycled to glucose by
trehalases. Even though the trehalose cycle consists of only a few metabolites
and enzymatic steps, its regulatory structure and operation are surprisingly
complex. The article begins with a review of experimental observations on the
regulation of the trehalose cycle in yeast and proposes a canonical model for
its analysis. The first part of this analysis demonstrates the benefits of the
various regulatory features by means of controlled comparisons with models of
otherwise equivalent pathways lacking these features. The second part
elucidates the significance of the expression pattern of the trehalose cycle
genes in response to heat shock. Interestingly, the genes contributing to
trehalose formation are up-regulated to very different degrees, and even the
trehalose degrading trehalases show drastically increased activity during
heat-shock response. Again using the method of controlled comparisons, the
model provides rationale for the observed pattern of gene expression and
reveals benefits of the counterintuitive trehalase up-regulation.

To induce a heat shock, set the parameter heat_shock from 0 to 1. This
changess the parameter values of X8 to X19 from 1 to the values given in table
3 of th eoriginal publication.  
As this is an S-systems model, it does not contain any reactions encoded in
SBML.


