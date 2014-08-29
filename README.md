SeqPlots
========

> An interactive tool for visualizing track signals and sequence motif densities along genomic features using average plots and heatmaps


## Introduction
The SeqPlots is universal, web browser based tool for plotting
average track signal (e.g. reads coverage) and sequence motif density over
user specified genomic features. The data are visualized on linear plot,
with error estimates as fields, or as series of heatmaps that can be sorted
and clustered. The dual-purpose implementation allows running the software
locally on desktop or deploying it on server. The unique features of our
software are collaboration and data sharing capabilities, as well as
ability to store pre-calculated result matrixes, that combine many
sequencing experiments and in-silico generated tracks with multiple
different features. These binaries can be further used to generate new
combination plots on fly, run automated batch operations or share with
colleagues, who can adjust their plotting parameters without loading actual
tracks and recalculating numeric values.

## Installation
```{r}
devtools::install_github('przemol/seqplots', 
  auth_token='5dc47e7bc3b49c07961d7528a796b8d5818451d4')
```