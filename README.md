## Natural Language Processing Tutorial
#### Julia Burek, Julia Deaver, Madeleine Jones, Chelsea Le Sage

This tutorial is intended to introduce students to natural language processing (NLP) concepts and to provide hands-on experience with a robust data set in R. Students will perform exploratory text analysis on wine review data (found on <a href="https://www.kaggle.com/datasets/zynicide/wine-reviews?datasetId=1442&language=R">Kaggle</a>) and ultimately perform sentiment analysis. 

#### Natural Language Processing
Natural language processing is the field of interaction between computers and human language. Useful R libraries for NLP include:
<ul>
  <li><a href="https://cran.r-project.org/web/packages/wordcloud/wordcloud.pdf">wordcloud</a> visualizes the similarities and differences between text documents</li>
  <li><a href="https://stringi.gagolewski.com">stringi</a> allows for fast text processing such as concatenation, searching, and normalization</li>
  <li><a href="https://cran.r-project.org/web/packages/tidytext/vignettes/tidytext.html">tidytext</a> provides the infrastructure for text mining</li>
  <li><a href="https://cran.r-project.org/web/packages/textdata/index.html">textdata</a>'s framework to parse through and store data</li>
  <li><a href="https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html">stringr</a> adds string functions for text manipulation and pattern matching</li>
</ul>

##### Exploratory Text Analysis

##### Sentiment Analysis

#### Dataset
The tutorial will be conducted with the `winemag-data-130k-v2.csv` data file. The `description` column provides tasting notes and flavor profiles for each wine. This is our column of interest for language processing. 
