# SkimLit: NLP Milestone Project

This project is focused on Natural Language Processing (NLP) and aims to automatically classify scientific abstracts from PubMed based on their structure (e.g., Background, Objectives, Methods, Results, Conclusions).

## Project Overview

SkimLit (Skimming Literature) is a deep learning project that leverages **TensorFlow**, **TensorFlow Hub**, and **Spacy** for efficient scientific literature classification. The goal is to assist researchers in quickly skimming through large amounts of literature by summarizing the key parts of a scientific abstract.

### Dataset

The dataset used in this project is a subset of the PubMed 200k RCT dataset, which contains randomized controlled trials.

## Installation

To get this project running, follow the steps below.

### 1. Clone the repository

```
git clone https://github.com/Sudhan09/Skim-Lit.git
cd Skim-Lit
```

### 2. Conda Environment Setup
You can set up the required environment using the provided *environment.yml* file:

```
conda env create -f environment.yml
conda activate skimlit-env
```

Alternatively, you can install the required packages using `requirements.txt`:

```
pip install -r requirements.txt
```

### Usage

Once the environment is set up, you can start by running the Jupyter notebook included in the repository.

### Run Jupyter Notebook

```
jupyter notebook
```
Open the `SkimLit_nlp_project.ipynb` notebook and run the cells to train and evaluate the model.

### Features

- **Data Preprocessing:** Preprocesses the scientific abstracts by tokenizing and creating word embeddings using TensorFlow and Spacy.
- **Modeling:** Uses TensorFlow models such as **EfficientNet** to classify text into respective sections of a scientific abstract.
- **Evaluation:** Includes accuracy and loss metrics to assess model performance.

### Large Files Warning

The dataset files, such as `.7z` and `.zip` formats, are large. It is recommended to use Git LFS (Large File Storage) to handle these files. For more information on setting up Git LFS, refer to Git [LFS Documentation](https://git-lfs.github.com/).



