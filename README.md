# NLP_spoiler
Final project for NLP class. Movie-books spoiler.

The purpose of this study is to analyze the phenomenon of spoiler-containing reviews in the entertainment industry. With the increasingly growing importance of online communities as source of information, it becomes essential to develop tools that make the user experience as spoiler-free as possible. For this purpose, a text classifier represents a valuable choice, compared to a baseline model that we set to be a Logistic Regression with TF-IDF embeddings.
An initial data exploratory analysis provides useful insights on the general trends of this phenomenon. Furthermore, we aim at rephrasing reviews our classifier labeled as "containing spoiler" with a spoiler-free  version, through a generative model.
Data is taken from the IMDB revies dataset, available on Kaggle and scraped from IMDB.com. It contains 1570 movies with plot summary and synopsis and a total of 573.906 reviews with text, ratings and spoiler flags (74% No vs 26% Yes).
To evaluate our classifier we will use the F1-score, with a strong focus on recall to prevent spoilers from being left on the pool of reviews. Instead, the generated paraphrasis will be evaluated against the original reviews using semantic similarity measures (i.e. STSBenchmark, etc.).


