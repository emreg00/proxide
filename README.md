
# ProXide

Jupyter (IPython) [Notebook](proxide.ipynb) and required files for the analysis 
presented in "Investigating side effect modules in the interactome and their use 
in drug adverse effect discovery".

## Data files

Drug-side effect associations and their closeness values assessed by various 
measures are given in "metrics_sider.dat" and "metrics_offsides", 
using SIDER and OFFSIDES databases, respectively. 
"module.dat" and "degree.dat" contain information
on the side effect modules and degrees of nodes in the network. 
"validation.dat" contains the prediction performance values. 
Gene symbol and ENTREZ gene id of the proteins in the side effect modules
can also be found in "side_effect_to_genes.tsv" and "side_effect_to_geneids.pcl"
files, respectively.

See [proximity](https://github.com/emreg00/proximity) and [toolbox](https://github.com/emreg00/toolbox) repositories for more information
on network-based proximity and its calculation.

## Required packages for the Notebook

- R kernel for Jupyter
- ROCR 
- ggplot2


