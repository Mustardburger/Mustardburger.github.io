---
title: "Deep learning for transcription factors binding sites predictions"
excerpt: >
    <p>Building deep learning models to predict cell-type specific transcription factor binding sites.</p>
tags: [comp_bio]
collection: projects
project_date: "January 2023 – June 2025"
---
**Publication (in preparation)**: _maxATAC-v2 infers nucleosome positions from single-cell ATAC-seq training data for improved genome-wide transcription factor binding site prediction_
**Poster presentations**:
* Senior Capstone 2025: [_Nucleosome positions improve cell-type specific transcription factor binding site predictions using deep-learning based maxATAC-v2_](https://drive.google.com/file/d/1Qbs4b270j7wr5orAyKhOpYk8ZJzfgd-v/view?usp=drive_link)
* CCHMC Immunology Retreat 2023: [_Improved transcription factor binding site predictions and benchmarking using deep-learning based maxATAC-v2 models_](https://drive.google.com/file/d/1aGas9JszzSGVS1SaQj1fN_y9-OazM1lW/view?usp=drive_link)

Transcription factors (TF) regulate gene expression by binding to specific DNA sequences called motifs. However, the presence of motifs does not guarantee TF binding in vivo, due to other epigenetics factors such as chromatin accessibility, DNA methylation marks, ... In this project, we investigate the use of deep learning to predict cell-specific TF binding across 127 human TFs, utilizing inputs from the reference DNA sequence and ATAC-seq signal. The work utilizes the transformer architecture to integrate multimodal epigenetic inputs and predict binding at 32-bp resolution.

My contributions include building the prototype transformer, benchmarking its performance on held-out hematopoietic stem cells, curating and cross-correlating bulk and single-cell ATAC-seq data, and leading analyses for attention matrix visualizations for interpretability.

My utmost gratitude to Dr. Matthew Weirauch and Dr. Emily Miraldi for allowing me to work on the project!

![maxATAC v2 final architecture](/images/projects/maxatac_v2_architecture.png)


