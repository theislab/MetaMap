# MetaMap

This repository describes the code and analyses accompanying the [MetaMap: An atlas of metatranscriptomic reads in human disease-related RNA-seq data](https://academic.oup.com/gigascience/article/7/6/giy070/5036539) manuscript.

The MetaMap bioinformatic pipeline screens human RNA-seq data for the presence of microbial and viral reads by re-inspecting the non-human-mapping read fraction. [Simon et al.](https://www.biorxiv.org/content/early/2018/02/22/269092) applied the pipeline to close to 150 terabytes of publicly available raw RNA-seq data from >17,000 samples from >400 studies relevant to human disease using state-of-the-art high performance computing systems from the [Leibniz Supercomputing Centre](https://www.lrz.de/services/compute/linux-cluster/) in Garching, Germany. 

1. Detailed information about the MetaMap pipeline and how to execute it on your own data can be found at [protocols.io](https://www.protocols.io/view/metamap-pipeline-msec6be).

2. An R based tutorial describing the statistical analysis of the resulting output can be found in Tutorial_statistical_analysis.html/Rmd files.

To facilitate interactive exploration of the MetaMap resource we have developed a [webtool (beta version)](https://github.com/theislab/metamap-web) accessible [here](http://146.107.176.18:3838/MetaMap/R/).
