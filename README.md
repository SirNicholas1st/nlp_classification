# nlp_classification
This project involves training a Spacy NLP model on a dataset of Steam reviews to classify them as positive or negative.

## Data Collection
The first step of the project is collecting data from the Steam website. The reviews were scraped in a previous project.

## Data Cleaning
The dataset is then cleaned by dropping empty review rows and columns that won't be needed for NLP. The data is checked for NaN values and balanced using an equal number of positive and negative reviews.

## Training the Model
The cleaned data is used to train a Spacy NLP model using binary classification. The model is trained to assign binary data to reviews, i.e., recommended or not recommended.

## Testing the Model
The saved model is then loaded and tested for a few reviews.

## Conclusion
This project showcases how Spacy NLP can be used to train a model to classify Steam reviews as positive or negative. The model can be further fine-tuned to improve accuracy, and the techniques used here can be applied to other NLP classification tasks.
