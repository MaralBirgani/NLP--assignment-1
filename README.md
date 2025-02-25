# NLP--assignment-1
# Wikipedia Text Classification Project

## Overview

This project, developed as part of the NLP course for a Master's degree in Artificial Intelligence at the University of Verona and it aims to classify English-language texts into two categories: "geographic" and "non-geographic." The classification is based on the content of Wikipedia articles, and the implementation includes techniques such as Naive Bayes classification and Logistic Regression.

## Features

- **Text Retrieval:** Utilizes the Wikipedia API to fetch text content for a given topic.
- **Pre-processing Techniques:**
  - Tokenization
  - Stop words removal
  - Snowball stop words removal
  - Porter Stemmer
  - WordNet Lemmatizer

- **Classification Methods:**
  - Naive Bayes Classification
    - Bag of Words without pre-processing
    - Bag of Words with Snowball stop words and Porter Stemmer
  - Logistic Regression
    - With and without pre-processing

## Requirements

- Python 3.x
- Required Python packages: `wikipedia-api`, `nltk`, `scikit-learn`

## Setup

1. Install the required packages:

    ```bash
    pip install wikipedia-api nltk scikit-learn
    ```

2. Download NLTK resources:

    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('stopwords')
    nltk.download('wordnet')
    ```


## Acknowledgments

- [Wikipedia API](https://www.mediawiki.org/wiki/API:Main_page)
- [NLTK Library](https://www.nltk.org/)
- [scikit-learn Library](https://scikit-learn.org/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
