# Movie Reviews Topic Modeling with LSA

This Python script performs topic modeling on movie reviews using Latent Semantic Analysis (LSA). The script utilizes the NLTK natural language processing library to tokenize and clean the text data. The cleaned text is then vectorized using the TF-IDF vectorizer in Scikit-learn. After that, the LSA model is fit on the resulting sparse matrix of document-term frequencies using Scikit Learn's TruncatedSVD implementation.

## Getting Started

### Prerequisites
This project requires the following dependencies installed:
- numpy
- pandas
- matplotlib
- nltk
- scikit-learn
- wordcloud

To install the above dependencies run:
```
pip install numpy pandas matplotlib nltk scikit-learn wordcloud
```

### Running the Script

1. Open your terminal and navigate to the directory containing the script.
2. Replace `"CSV FILE PATH"` at line number 23 with the path of your csv file containing movie reviews data.
3. Run the following command:
```
python script_name.py
```
4. Wait for the topic modeling process to complete.
5. Once the process completes, you should be able to see the following outputs:
   - A list of top topics and their corresponding scores.
   - A set of word clouds representing the top terms for each topic.
   - The perplexity score of the LSA model.
