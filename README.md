# HW3-Movie-Plots

This [Dataset ](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots?resource=download) contains information about different movies such as titles, plots, actors and release year. For this assignment, we wanted to create a search tool that helps the users find relevant movies based off of the query they enter.

We will be utilizing a Semantic search model, A Reranking model and a RAG (Retrieval Augmented Generation) model. 

## Before Using

We are only going to focus on the first 1000 movies: 

```
from datasets import load_dataset
ds = load_dataset("Coder-Dragon/wikipedia-movies", split='train[:1000]')
```
The notebooks provided were run using Google Colabs T4 GPU Runtime, in addition please check the [requirements.txt](https://github.com/Jstallard44/HW3-Movie-Plots/blob/main/requirements.txt) file for the necessary dependencys 
