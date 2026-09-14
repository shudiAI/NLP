# Lab 4: Classification and Evaluation in NLP

This lab focuses on text classification and model evaluation using sentiment analysis.

The notebook includes an example using the Disneyland Reviews dataset and a sentiment classification task using the Amazon Unlocked Mobile Phones Reviews dataset.

## Tasks

1. Load the dataset and apply five preprocessing steps.
2. Split the data into training and testing sets.
3. Extract text features using TF-IDF.
4. Train a Multinomial Naive Bayes classifier.
5. Evaluate the model using accuracy and a classification report.
6. Print the confusion matrix.

## Datasets

### Disneyland Reviews Dataset
Kaggle:
https://www.kaggle.com/datasets/arushchillar/disneyland-reviews

Expected file name:
`DisneylandReviews.csv`

### Amazon Unlocked Mobile Phones Reviews Dataset
Kaggle:
https://www.kaggle.com/datasets/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones

Expected file name:
`Amazon_Unlocked_Mobile.csv`

> **Note:** The datasets are not included with this lab because of their large file size.  
> Please download them directly from Kaggle and upload the CSV files to Google Colab before running the notebook.

## Required Libraries

- pandas
- re
- scikit-learn

## How to Run

1. Open the `.ipynb` file in Google Colab.
2. Download the required datasets from Kaggle.
3. Upload the CSV files to the Colab session.
4. Make sure the file names match the names used in the notebook.
5. Run the cells in order from top to bottom.

## Main Techniques Used

- Text preprocessing
- Train/test split
- TF-IDF feature extraction
- Multinomial Naive Bayes
- Accuracy score
- Classification report
- Confusion matrix
