# NLP_spoiler
Final project for NLP class. Movie-books spoiler.

The purpose of this study is to analyze the phenomenon of spoiler-containing reviews in the entertainment industry. With the increasingly growing importance of online communities as source of information, it becomes essential to develop tools that make the user experience as spoiler-free as possible. 
After an initial data exploratory analysis that provides useful insights on the general trends of this phenomenon, we develop a text classifier with the purpose of identifying those reviews that contain spoiler content. Furthermore, through the use of a generative model, we rephrase such reviews into a new spoiler-free version.
The data we analyze is taken from a Kaggle dataset containing movie reviews scraped from IMDB.com. It contains information on 1570 movies such as their plot summary and synopsis, as well as a total of 573.906 reviews with their text content, ratings and spoiler flags (74% No vs 26% Yes).

To evaluate our classifier we will use the F1-score, with a strong focus on recall to prevent spoilers from being left on the pool of reviews. The performance of our model will then be compared to that of a  Logistic Regression with TF-IDF embeddings, serving as a baseline. As a final step, the generated paraphrasis will be evaluated against the original reviews using semantic similarity measures (i.e. STSBenchmark, etc.).
s

