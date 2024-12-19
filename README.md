This repository contains code for a query algorithm for the academic database, ArXiv, in the notebook "Arxiv Navigator Algorithm". The algorithm takes as input up to three keywords, up to two ArXiv topics, a targets year, and desired page and figure counts. It then uses cosine similarity and other ranking metrics to determine the top three authors in the search domain and creates an undirected graph for each author linking relevant articles. The graph can be viewed as an SVG file in the user browser.

Steps for running are as follows:

1. Download the ArXiv dataset from [Kaggle](https://www.kaggle.com/datasets/Cornell-University/arxiv)
2. Run the  "Arxiv Normalization" notebook with this file to generate a cleaned version of the data (you can adjust how much of the data is used for the algorithm here)
3. Run the "Arxiv Navigator Algorithm" notebook. Make sure that you change the "top_three" function input based on your desired query
