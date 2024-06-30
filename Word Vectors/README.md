This project is the third part of a programming assignment that explores word vectors in natural language processing (NLP). Word vectors represent each word as a vector of numbers, encoding the meaning of the word. This project includes various exercises to understand and use word vectors.

## Table of Contents
1. [Predict the Countries from Capitals](#predict-the-countries-from-capitals)
    - [Importing the Data](#importing-the-data)
    - [Cosine Similarity](#cosine-similarity)
    - [Euclidean Distance](#euclidean-distance)
    - [Finding the Country of each Capital](#finding-the-country-of-each-capital)
    - [Model Accuracy](#model-accuracy)
2. [Plotting the vectors using PCA](#plotting-the-vectors-using-pca)
3. [How to Run](#how-to-run)
4. [Requirements](#requirements)

## Predict the Countries from Capitals
In this part of the assignment, we predict the countries that correspond to some capitals using NLP. The exercises included in this part are:

### Importing the Data
We start by importing essential Python libraries and loading the dataset as a Pandas DataFrame.

### Cosine Similarity
We implement a function `cosine_similarity` that takes in two word vectors and computes the cosine distance between them.

```python
def cosine_similarity(A, B):
    dot = np.dot(A, B)    
    norma = np.linalg.norm(A)
    normb = np.linalg.norm(B)    
    cos = dot / (norma * normb)
    return cos
