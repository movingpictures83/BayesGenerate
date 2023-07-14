# BayesGenerate
# Language: Python
# Input: TXT
# Output: PREFIX
# Tested with: PluMA 1.1, Python 3.6
# Dependency: numpy==1.19.1, scipy==1.4.1

This plugin creates sample data sets for constructing a bayesian network and dynamic bayesian notworks with and without time-warping

The plugin takes as input a tab-delimited file of keyword-value pairs:

annotated: TSV file of annotations
selected: TSV file of selected taxa
alignment: TSV file of alignment

Output networks will be generated as TSV files using the user-specified prefix
