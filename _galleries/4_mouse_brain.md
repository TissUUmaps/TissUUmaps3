---
title: "Automated identification of the mouse brain's spatial compartments from in situ sequencing data"
feature_image: "/assets/gallery_images/automated.png"
link: "https://tissuumaps-demo.serve.scilifelab.se/mousebrain_5.tmap"
---

Neuroanatomical compartments of the mouse brain are identified and outlined mainly based on manual annotations of samples using features related to tissue and cellular morphology, taking advantage of publicly available reference atlases. However, this task is challenging since sliced tissue sections are rarely perfectly parallel or angled with respect to sections in the reference atlas and organs from different individuals may vary in size and shape and requires manual annotation. Here, we show how in situ sequencing data combined with dimensionality reduction and unsupervised clustering can be used to identify spatial compartments that correspond to known anatomical compartments of the brain. Here we show results on four different sections of mouse brains.

More information is available in this [publication](https://doi.org/10.1186/s12915-020-00874-5){:target="_blank"}: \
<small>G. Partel, M.M. Hilscher, G. Milli, L. Solorzano, A.H. Klemm, M. Nilsson, and C. Wählby.  Automated identification of the mouse brain’s spatial compartments from in situ sequencing data.  BMC Biology, <https://doi.org/10.1186/s12915-020-00874-5>{:target="_blank"}, Oct 2020.</small>

**TissUUmaps interactive viewer**: 
<a href='https://tissuumaps-demo.serve.scilifelab.se/mousebrain_5.tmap' target="_blank" class="button">Mouse brain</a>

The original raw ISS data was published in Qian, X., Harris, K. D., Hauling, T., Nicoloutsopoulos, D., Muñoz-Manchado, A. B., Skene, N., ... & Nilsson, M. (2020). Probabilistic cell typing enables fine mapping of closely related cell types in situ. [Nature methods](https://doi.org/10.1038/s41592-019-0631-4){:target="_blank"}, 17(1), 101-106. 

Data and code availability: All software was developed in Python 3 using open source libraries, and data processing of pipeline workflows was carried out using [Anduril2](https://doi.org/10.1093/bioinformatics/btz133) analysis framework. The processing pipelines, data, and the software version used to generate the analysis results and figures presented in this paper are available at <https://doi.org/10.5281/zenodo.3928219>{:target="_blank"} or from our github repository <https://github.com/wahlby-lab/graph-iss>{:target="_blank"}. 