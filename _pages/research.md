---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

# Research Projects

## [PlantCaduceus: A DNA Language Model for Plant Genomics](https://doi.org/10.1073/pnas.2421738122)

PlantCaduceus, with its short name of PlantCAD, is a plant DNA LM based on the [Caduceus](https://arxiv.org/abs/2403.03234) architecture, which extends the efficient [Mamba](https://arxiv.org/abs/2312.00752) linear-time sequence modeling framework to incorporate bi-directionality and reverse complement equivariance, specifically designed for DNA sequences. PlantCAD is pre-trained on a curated dataset of 16 Angiosperm genomes. PlantCAD showed state-of-the-art cross species performance in predicting TIS, TTS, Splice Donor and Splice Acceptor. The zero-shot of PlantCAD enables identifying genome-wide deleterious mutations and known causal variants in Arabidopsis, Sorghum and Maize.

![PlantCaduceus Model](/images/plantcad.jpg)

## [PlantCAD2: A Long-Context Plant DNA Language Model](https://www.biorxiv.org/content/10.1101/2025.08.27.672609v1)

PlantCAD2 is the updated version of PlantCaduceus (PlantCAD), extending it with a longer context window and broader pre-training to improve cross-species genomics modeling and annotation.

[Code on GitHub](https://github.com/kuleshov-group/PlantCaduceus)

![PlantCAD2 Model](/images/plantcad2.jpg)

Understanding how DNA sequence encodes biological function remains a fundamental challenge in biology. Flowering plants (angiosperms), the dominant terrestrial clade, exhibit maximal biochemical complexity, extraordinary species diversity (over 100,000 species), relatively recent origins (∼160 million years), ∼200-fold variation in genome size and relative compact coding regions compared with other eukaryotes. These features present both a unique challenge and opportunity for pre-training DNA language models to understand plant-specific evolutionary conservation, regulatory architectures and genomic functions. Here, we introduce PlantCAD2, a long-context, plant-specific DNA language model with single-nucleotide resolution, pre-trained on 65 angiosperm genomes, together with a series of public benchmarks for evaluation. Comprehensive zero-shot testing shows that PlantCAD2 (676 million parameters) efficiently captures evolutionary conservation, surpassing the 7-billion-parameter Evo2 model in 10 of 12 tasks. With parameter-efficient fine-tuning, PlantCAD2 also outperforms the 1-billion-parameter AgroNT across seven cross-species tasks. Moreover, its 8 kb context window substantially improves accessible chromatin prediction in large genomes such as maize (AUPRC increasing from 0.587 to 0.711), underscoring the importance of long-range context for modeling distal regulation. Together, these results establish PlantCAD2 as a powerful, efficient, and versatile foundation model for plant genomics, enabling accurate genome annotation across diverse species.

## [deepTFBS: Transcription Factor Binding Site Prediction](https://advanced.onlinelibrary.wiley.com/doi/full/10.1002/advs.202503135)

I developed deepTFBS, a method for transcription factor binding site prediction that uses multi-task and transfer learning approaches to improve cross-species prediction accuracy.

![deepTFBS Model](/images/tfbs.jpg)


## Epitranscriptome Analysis Platforms

I developed a series of platforms for plant epitranscriptome analysis, including [deepEA](https://academic.oup.com/plphys/article/185/1/29/5988724), [PEA](https://academic.oup.com/bioinformatics/article/34/21/3747/5021690), and [PEA-m5C](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2018.00519/full), which allow for interactive analysis of epitranscriptome sequencing data.

![Epitranscriptome Analysis](/images/deepea.png)
