
# Sarcasm Detection in Social Media Texts

## Project Overview
This repository contains code for detecting sarcasm in Reddit and Twitter posts using deep learning models. The system implements three architectures: GloVe-BiLSTM, Regularized Attention Model, and FastText Hybrid.

## Project Structure

sarcasm-detection/
├── data/ # Raw dataset files 
│ ├── twitter_training.jsonl
│ ├── twitter_testing.jsonl
│ ├── reddit_training.jsonl
│ └── reddit_testing.jsonl
│
├── models/ # Saved model checkpoints
│ ├── basic model(no regularization).h5
│ ├── basic model(with regularization).h5
│ └── fastText_model.h5
│
├── CASUAL SARCASM.ipynb/ 
├── readme.md
└── requirements.txt

dataasets link: https://github.com/EducationalTestingService/sarcasm/tree/master

## Installation

### Required Libraries
```bash
Python 3.8+ with the following package versions:

Package	Version
tensorflow	2.10.0
pandas	1.5.3
numpy	1.23.5
scikit-learn	1.2.2
matplotlib	3.7.0
seaborn	0.12.2
nltk	3.8.1
gensim	4.3.0

Dataset Setup
Download Datasets (Available upon request):

Twitter: SARC Twitter Dataset

Reddit: SARC Reddit Dataset

File Placement:

bash
mkdir -p data/
# Place downloaded files in data/ directory
Pre-trained Embeddings:

Download GloVe 300D

Download FastText


Hardware Requirements
Minimum: 8GB RAM, 4-core CPU

Recommended: 16GB+ RAM, GPU with 8GB+ VRAM

Tested on: NVIDIA RTX 3060, 32GB RAM

License
MIT License. See LICENSE for full text.

Dataset Access
The datasets used in this project are available for research purposes. Contact your.name@institution.com for access requests.
