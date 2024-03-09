# Project 3

## Problem Statement
Rank candidates' qualification for an HR job based on their job title and connection number. 

## Approach
The cosine similiarity of job titles against the keywords is obtained by using BERT and Sentence Transformer. The initial rank is based on the average cosine similiarity. A few candidates are then starred manually and then LightGBM Ranker algorithm is then used to re-rank the candidates.
