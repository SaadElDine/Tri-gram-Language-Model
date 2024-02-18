# Tri-gram-Language-Model for Text Generation

This Python script implements a trigram model for text generation based on a given dataset of words. The model calculates the probabilities of character sequences of length three (trigrams) and uses these probabilities to generate new text.

![image](https://github.com/SaadElDine/Tri-gram-Language-Model/assets/113860522/21ffa5a0-b11e-47ca-95b4-3caf1c53b386)


## Implementation

The implementation involves the following steps:

1. Reading a dataset of words from a file (`names.txt`).
2. Tokenizing the words into individual characters and adding padding to the beginning and end of each word.
3. Counting the occurrences of trigrams in the dataset.
4. Applying Laplace (add-one) smoothing to the trigram counts to avoid zero probabilities.
5. Generating text using the trigram model by sampling from the smoothed probabilities.
6. Calculating the perplexity of the model based on the first 15 words in the dataset.

## Usage

1. Ensure you have Python and the required libraries (`torch`) installed.
2. Download the dataset file (`names.txt`) using the provided link.
3. Run the Python script to train the trigram model and generate text.

