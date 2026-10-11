---
title: "DEPICTER: Deep representation clustering for histology annotation"
feature_image: "/assets/gallery_images/depicter.png"
link: "https://depicter-2024.serve.scilifelab.se/patient_022_node_4.tmap?path=DEPICTER/camelyon"
---

DEPICTER (Deep rEPresentatIon ClusTERing) is an interactive segmentation tool for histopathology annotation that produces a patch-wise dense segmentation map at WSI level. The interactive nature of DEPICTER leverages self- and semi-supervised learning approaches to allow the user to participate in the segmentation producing reliable results while reducing the workload. DEPICTER consists of three steps: first, a pretrained model is used to compute embeddings from image patches. Next, the user selects a number of benign and cancerous patches from the multi-resolution image. Finally, guided by the deep representations, label propagation is achieved using our novel seeded iterative clustering method or by directly interacting with the embedding space via feature space gating.

More information is available in this [publication](https://doi.org/10.1016/j.compbiomed.2024.108026){:target="_blank"}: \
<small>Chelebian, E., Avenel, C., Ciompi, F., & Wählby, C. (2024). DEPICTER: Deep representation clustering for histology annotation. Computers in Biology and Medicine, 108026.  doi: <https://doi.org/10.1016/j.compbiomed.2024.108026>{:target="_blank"}</small>

A demo of DEPICTER with the **CAMELYON17** dataset can be found here: <a href='https://depicter-2024.serve.scilifelab.se/patient_022_node_4.tmap?path=DEPICTER/camelyon' target="_blank" class="button">DEPICTER on CAMELYON</a> \
<small>
