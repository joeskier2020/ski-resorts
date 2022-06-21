# ski-resorts
This repository contains descriptive reviews and statistics on ski resorts.

There are three Jupyter Notebook files which contain the analysis.  The notebooks 
are intended to be read through and the accompany python code and results
are included in the file.  

1) NLTK By Review.ipynb

This file contains some Natural Language Processing of ski resort reviews.  The 
reviews are broken down by number of stars given in each review.  Some common 
words are identified.  The text is pre-processed.  And a TFIDF analysis is 
completed.  Some visualization of the data are also included.   

Finally, a named entity and parts of speech tagging is started.  And leaves room
for further analysis.  

2) NLTK By Ski Center.ipynb

This file is similar to the above Jupyter Notebook file.  Instead of grouping the 
corpus and documents by the number of star;  the corpus is grouped into documents
which contain all the reviews for specific ski centers.  

The same pre-processing and common word analysis is done, but grouped by ski center 
instead.  A TFIDF analysis is also completed.  Visualizations of data are included.

3)  Ski Resort Stats.ipynb

This Jupyter Notebook file uses a different data set.  This dataset is quantitative 
and includes multiple columns of statistics on ski centers.  Some key variables are 
analyzed and plotted.  Some interesting insights are revealed by the data.  

4)  OnTheSnow_SkiAreaReviews.csv

This is a comma seperated file which contains thousands of text based reviews on ski 
centers in the United States.  There are over 290 ski centers which have been reviewed.
The first two Jupyter Notebook files above use this text file.

5)  skiResort.xlsx

This is an excel based data source which has quantitative statistics about ski resorts 
from all over the world.  The third Jupyter Notebook file analysis these statistics for 
the ski resorts in the United States.  
