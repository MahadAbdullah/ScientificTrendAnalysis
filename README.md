﻿# ScientificTrendAnalysis

This project utilizes various unsupervised machine learning algorithms to help identify trends in science.
It uses the [arXiv dataset](https://www.kaggle.com/datasets/Cornell-University/arxiv) which contains over 2.4 million papers as of January 2024.

## Exploratory Visualizations

The [exploratory-visualizations](https://github.com/MahadAbdullah/ScientificTrendAnalysis/blob/main/exploratory-visualizations.ipynb) file uses the pre-defined categories provided in the dataset itself to show certain topics that are popular.

## Topic Extraction

The [topic-extraction](https://github.com/MahadAbdullah/ScientificTrendAnalysis/blob/main/topic-extraction.ipynb) file uses the TF-IDF algorithm along with other unsupervised machine learning algorithms to extract words from the abstracts of each paper and then cluster them. The purpose of this is to create more consistent dataset categories than the ones already provided.
