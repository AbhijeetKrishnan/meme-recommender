# Meme Recommendation System

![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

A meme recommendation system that uses item-to-item similarity to recommend memes to users. It clusters memes via K-means using features from 
[Inception v3](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Szegedy_Rethinking_the_Inception_CVPR_2016_paper.html), 
[HOG](https://ieeexplore.ieee.org/abstract/document/1467360/),[KAZE](https://link.springer.com/chapter/10.1007/978-3-642-33783-3_16) and
PCA.

The dataset used is the [Reddit Memes Dataset](https://www.kaggle.com/sayangoswami/reddit-memes-dataset) by [Sayan Goswami](https://www.kaggle.com/sayangoswami) from Kaggle.

## Installation

Use the environment manager [mamba](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html) to install the required packages.

```bash
git clone git@github.com:AbhijeetKrishnan/meme-recommender.git
cd meme-recommender
mamba env create -f environment.yml
mamba activate meme-recommender
```

## Dataset

Obtain the dataset from [Kaggle](https://www.kaggle.com/datasets/sayangoswami/reddit-memes-dataset) and place it in the `data` folder (create one if necessary).

```bash
unzip data/archive.zip -d data
mv data/memes/memes/* data/memes
rmdir data/memes/memes
rm data/archive.zip
```

## Usage

TODO: Add usage instructions