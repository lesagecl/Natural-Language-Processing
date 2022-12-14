## Natural Language Processing Tutorial
#### Julia Burek, Julia Deaver, Madeleine Jones, Chelsea Le Sage

This tutorial is intended to introduce students to natural language processing (NLP) concepts and to provide hands-on experience with a robust data set in R. Students will perform exploratory text analysis on wine review data (found on <a href="https://www.kaggle.com/datasets/zynicide/wine-reviews?datasetId=1442&language=R">Kaggle</a>) and ultimately perform the following machine learning techniques:
<ul>
  <li>Sentiment Analysis</li>
  <li>Term Frequency - Inverse Document Frequency Analysis</li>
  <li>K Means Clustering</li>
</ul>

#### Natural Language Processing
Natural language processing is the field of interaction between computers and language. It is the process of teaching computers how to understand text, in the same ways that humans are able to. Useful R libraries for NLP include:
<ul>
  <li><a href="https://cran.r-project.org/web/packages/wordcloud/wordcloud.pdf">wordcloud</a>: visualize the similarities and differences between text documents</li>
  <li><a href="https://stringi.gagolewski.com">stringi</a>: fast text processing such as concatenation, searching, and normalization</li>
  <li><a href="https://cran.r-project.org/web/packages/tidytext/vignettes/tidytext.html">tidytext</a>: infrastructure for text mining</li>
  <li><a href="https://cran.r-project.org/web/packages/textdata/index.html">textdata</a>: framework to parse through and store data</li>
  <li><a href="https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html">stringr</a>: add string functions for text manipulation and pattern matching</li>
</ul>

##### Exploratory Text Analysis (ETA)
Performing ETA is a crucial first step for understanding the underlying trends or differences among our data. It enables us to check hypotheses and generate key insights in a streamlined way.

##### Sentiment Analysis
Sentinment analysis allows us to understand the emotions associated with words. By performing sentiment analysis on products, companies can often get insight to how a customer may respond to their product. 

#### Dataset
The tutorial will be conducted with the `winemag-data-130k-v2.csv` data file. The `description` column provides tasting notes and flavor profiles for each wine. This is our column of interest for language processing. 

Estimated time to complete tutorial: 60 minutes
