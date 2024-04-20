# NLP_spoiler
Final project for NLP class. Movie-books spoiler.

Descriptive analysis of the spoilers over time that justifies the choice of a classifier to filter spoiler reviews. We wanted to find the spoiler reviews and rephrase them with a generative model. For this task we would evaluate different transformer models and pick the best. We also carry out a text similarity clustering on the plot summaries/synopses (that do contain spoilers) to gather insights on how to combine movies according to similar plots, rather than similar genres/topics as a common recommender would do. As a further study, we would carry out the same similarity clustering on the reviews to see if the same clustering logic used above can be applied to the reviews of similar movies. 

Data is taken from the IMDB revies dataset, available on Kaggle and scraped from IMDB.com. It contains 1570 movies with plot summary and synopsis and a total of 573.906 reviews with text, ratings and spoiler label (74% No vs 26% Yes), let alone other columns.

To conclude, the evaluation method will be the micro f1-score for the classifier, with strong focus on recall to prevent spoilers from being left on the pool of reviews. 

