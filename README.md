# Text Mining Project

## About
This project explores the impact of contextual attention on Arabic text classification. We analyze attention mechanisms and their usefulness in transformers and generative models for Arabic text classification.

## Dataset
The dataset used in this project includes Arabic text data that has been preprocessed for classification tasks. The preprocessing steps include cleaning, stemming, and lemmatization.

## Models
We have implemented several models for text classification:
- **LSTM Model**: A Long short-term memory model for text classification.
- **CNN Model**: A convolutional neural network model for text classification.
- **AraBERT Model**: A transformer-based model specifically designed for Arabic text.

## Notebooks
- `arabic-text-classification.ipynb`: Notebook containing the CNN model and LSTM model implemented.
- `arabic-text-classification-arabert.ipynb`: Notebook with the AraBERT model implementation.
- `preprocessing.ipynb`: Notebook detailing the exploratory data analysis (EDA) and preprocessing steps.
- `processing-files.ipynb`: Notebook that processes the files so it will create my dataset.

## Files
- `dataset.csv`: The saved dataset after processing.
- `train_data.csv`: The training dataset after doing the Data augmenting to categories that needs more articles. We used a creative technique which is summarize the article by using a pretrained model from Hugging face  then give the output of that summary to another model that can generate next words like gpt model
