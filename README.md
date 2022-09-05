# Sentiment Analysis using word embedding and Convolutional Neural Networks on Keras

Imdb has released a database of 50,000 movie reviews classified in two categories: Negative and Positive. This is a typical sequence binary classification problem.

The Movie Review Data is a collection of movie reviews retrieved from the imdb.com website in the early 2000s by Bo Pang and Lillian Lee. The reviews were collected and made available as part of their research on natural language processing.

The reviews were originally released in 2002, but an updated and cleaned up version were released in 2004, referred to as “v2.0”.

The dataset is comprised of 1,000 positive and 1,000 negative movie reviews drawn from an archive of the rec.arts.movies.reviews newsgroup hosted at imdb.com. The authors refer to this dataset as the “polarity dataset.”

The dataset will be downloaded automatically if not present on your disk.

Training should take ~20min. Accuracy should be ~88%.

### Data Preparation
There are 3 things done in this step.
1. Separation of data into training and test sets.
2. Loading and cleaning the data to remove punctuation and numbers.
3. Defining a vocabulary of preferred words.

### Training the model

<img width="741" alt="Screenshot 2022-09-05 at 4 21 56 PM" src="https://user-images.githubusercontent.com/26003031/188488690-99b2fd1c-7314-4b02-8339-52d1b0b38f78.png">
The model summary used for the sentiment analysis.
