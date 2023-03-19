# transformer-text-classification

## Problem + Why: 
The engine behind the news app processes almost 100k news articles every day in many languages and context. In order to connect people with the right content, need to know what the articles are about.

## Solution: 
Improve current recomendation algorithm of the app or better personalized content for the readers. 
So I needed to build a classifier that identify the category of an article accurately. 

## Data + Model: 
The 20 newsgroups dataset(scikit-learn) comprises around 18k newsgroups posts on 20 topics split in two subsets. 

1. Logistic regression accuracy=83%
2. Transformer architecture DistilBERT HF accuracy=82%


