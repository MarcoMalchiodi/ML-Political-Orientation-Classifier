# Political Orientation Classifier


This ML project offers a comprehensive solution to classify news articles into distinct political orientations, aiding users in understanding the underlying biases and perspectives shaping public discourse.

The project comprises a series of intricately connected components:

1) Scraping Applications:
url_scraping.py: This application retrieves a list of URLs containing news articles from diverse sources.
news_scraping.py: Upon obtaining URLs, this application extracts the text content of the articles in a raw format.

2) Data Cleaning (cleaner.py):
Once the text data is collected, the cleaner.py script plays a pivotal role in preprocessing the raw text, eliminating redundant information, such as HTML tags, advertisements, and other noise, to ensure the integrity and quality of the dataset.

3) Machine Learning Pipeline (news_classifier.ipynb):
- Data Preprocessing: The collected text data undergoes preprocessing steps such as tokenization, stop-word removal, and possibly stemming or lemmatization to prepare it for analysis.
- Word Embedding (Word2Vec): The textual data is transformed into numerical vectors using the Word2Vec embedding technique, which captures semantic relationships between words, providing a dense representation of the vocabulary.
- Model Building: Leveraging the scikit-learn library, a Naive Bayes classifier is trained on the embedded text data. Naive Bayes classifiers are well-suited for text classification tasks due to their simplicity and effectiveness in handling high-dimensional data.

