# Detecting novelty in USPTO patent applications with neural networks
This repository contains the project 2 of **EPFL CS-433 Machine Learning**. 

**Team name**: Novae

**Team members**: Giacomo Orsi, Vittorio Rossi, Chun-Tso Tsai

**Lab**: [Entrepreneurship and Technology Commercialization Chair](https://www.epfl.ch/labs/entc/), EPFL

## Abstract 
Despite providing a publicly accessible definition of novelty, the United State's Patents and Trademarks Office (USPTO) receives tens of thousands of non-compliant utility applications every year. This paper provides information regarding the non-linear correlations between a patent application's data and its novelty, and describes a model which predicts whether a patent will be approved. 


The paper which describes this project can be found [here](paper.pdf)


## Repository content
This repository contains the source code of the analysis carried out for the project. 

### `feature-selection.ipynb`
This notebook contains the query executed on Google Cloud BigQuery in order to build the datasets as described in the paper. 

### `claim2vec.ipynb`
This notebook contains the process of converting patent claims into vector representations using `word2vec`. The trained `word2vec` model can be found [here](https://drive.google.com/drive/folders/1FMzzzCLMi67CuvkCXQ7kRgh5qqJwIKOg?usp=sharing)

### `NN_classifier.ipynb`
This notebook contains the neural network design, training, and evaluation. The testing can be executed using the trained neural network that can be found [here](https://drive.google.com/drive/folders/1FMzzzCLMi67CuvkCXQ7kRgh5qqJwIKOg?usp=sharing)


## Datasets
The datasets that we generated are accessible in [this](https://drive.google.com/drive/folders/1LyoBf9eJzJajI4hSO2bt91eAD1bEZUMa?usp=sharing) Google Drive folder (EPFL authentication required).

The computed vectorization of the patent applications included in the dataset we generated is accessible [here](https://drive.google.com/drive/folders/1HryfK3vr1WSkBgu-UQx0Cgtu6k11ipq3?usp=sharing). 
