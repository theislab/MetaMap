# MetaMap

This repository describes the code and analyses accompanying the [MetaMap: An atlas of metatranscriptomic reads in human disease-related RNA-seq data](https://academic.oup.com/gigascience/article/7/6/giy070/5036539) manuscript.

The MetaMap bioinformatic pipeline screens human RNA-seq data for the presence of microbial and viral reads by re-inspecting the non-human-mapping read fraction. [Simon et al.](https://academic.oup.com/gigascience/article/7/6/giy070/5036539) applied the pipeline to close to 150 terabytes of publicly available raw RNA-seq data from >17,000 samples from >400 studies relevant to human disease using state-of-the-art high performance computing systems from the [Leibniz Supercomputing Centre](https://www.lrz.de/services/compute/linux-cluster/) in Garching, Germany. 

1. Detailed information about the MetaMap pipeline and how to execute it on your own data can be found at [protocols.io](https://www.protocols.io/view/metamap-pipeline-msec6be).

2. An R based tutorial describing the statistical analysis of the resulting output can be found in Tutorial_statistical_analysis.html/Rmd files.

3. To facilitate interactive exploration of the MetaMap resource we have developed a webtool. By clicking on the following link you can access the webtool and agree with our data protection policy (as outlined [here](https://www.helmholtz-muenchen.de/en/imprint/index.html)): **[MetaMap webtool](http://146.107.176.18:3838/MetaMap/R/)**. The code used to create the webtool can be found [here](https://github.com/theislab/metamap-web).


link to site: 

<iframe width="600" height="400" seamless frameborder="0" scrolling="no" src="http://146.107.176.18:3838/MetaMap/R/" ></iframe>
