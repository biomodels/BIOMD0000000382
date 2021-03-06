# BIOMD0000000382: Sturis1991_InsulinGlucoseModel_UltradianOscillation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000382.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000382.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000382 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Computer model for mechanisms underlying ultradian oscillations of insulin and glucose. **   
Sturis J, Polonsky KS, Mosekilde E, Van Cauter E. _Am J Physiol._1991
May;260(5 Pt 1):E801-9. [2035636](http://www.ncbi.nlm.nih.gov/pubmed/2035636),  
**Abstract:**   
Oscillations in human insulin secretion have been observed in two distinct
period ranges, 10-15 min (i.e. rapid) and 100-150 min (i.e., ultradian). The
cause of the ultradian oscillations remains to be elucidated. To determine
whether the oscillations could result from the feedback loops between insulin
and glucose, a parsimonious mathematical model including the major mechanisms
involved in glucose regulation was developed. This model comprises two major
negative feedback loops describing the effects of insulin on glucose
utilization and glucose production, respectively, and both loops include the
stimulatory effect of glucose on insulin secretion. Model formulations and
parameters are representative of results from published clinical
investigations. The occurrence of sustained insulin and glucose oscillations
was found to be dependent on two essential features: 1) a time delay of 30-45
min for the effect of insulin on glucose production and 2) a sluggish effect
of insulin on glucose utilization, because insulin acts from a compartment
remote from plasma. When these characteristics were incorporated in the model,
numerical simulations mimicked all experimental findings so far observed for
these ultradian oscillations, including 1) self-sustained oscillations during
constant glucose infusion at various rates; 2) damped oscillations after meal
or oral glucose ingestion; 3) increased amplitude of oscillation after
increased stimulation of insulin secretion, without change in frequency; and
4) slight advance of the glucose oscillation compared with the insulin
oscillation.(ABSTRACT TRUNCATED AT 250 WORDS)

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


