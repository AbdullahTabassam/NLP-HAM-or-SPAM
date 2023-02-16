# NLP Spam or Ham Classifier

This project is a Spam and Ham classifier using basic Natural Language Processing (NLP) techniques. It aims to classify messages as either spam or ham (non-spam) based on their content. The classification is performed using a Random Forest classifier and various NLP preprocessing steps.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

The NLP Spam or Ham Classifier project uses a machine learning approach to classify text messages. It employs NLP techniques such as removing punctuation, tokenizing, lemmatizing, and vectorizing using TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer. The classifier is trained on a labeled dataset to distinguish between spam and ham messages.

## Dataset

The dataset used in this project consists of labeled text messages, where each message is labeled as either spam or ham. The dataset also includes additional features such as the length of the text and the percentage of punctuation characters compared to other characters. The dataset is provided along with the code in the form of a Jupyter Notebook.

## Installation

To run the code locally, Clone the repository:

   git clone https://github.com/AbdullahTabassam/NLP-HAM-or-SPAM.git


## Usage

The main code for the project is available in the Jupyter Notebook file NLP_Ham_or_Spam_Classifier.ipynb. You can open the notebook using Jupyter Notebook or JupyterLab.

The notebook provides step-by-step instructions on data preprocessing, feature extraction, model training, and evaluation. You can run each cell in the notebook to execute the code and see the results.
## Results

The project initially uses a Random Forest classifier with randomly selected hyperparameters to evaluate the model. Evaluation metrics such as accuracy, precision, recall, and F1-score are calculated.

Furthermore, GridSearchCV is implemented to find the best parameters for the Random Forest model. The evaluation is performed again using the optimized model.

The results and performance metrics are discussed in the notebook, along with visualizations to provide insights into the classifier's performance.
## Contributing

Contributions to this project are welcome! If you have any suggestions, ideas, or bug fixes, please open an issue or submit a pull request.