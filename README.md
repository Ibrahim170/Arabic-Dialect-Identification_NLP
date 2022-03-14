# Arabic-Dialect-Identification


## Project Description

This is  repository contains the implementation of Basic Machine Learning Model and MarBert Transformer 
for the task of Dialect Identification.
Dialect identification is the task of automatically detecting the source variety of a given text or speech segment. 


## Dataset
QCRI Arabic Dialects Identification (QADI) is a Country-level Arabic dialects identification (DI) dataset. It provides a collection for benchmarking DI task.The dataset contains 540,590 tweets from 18 Arab countries.


[you can download dataset from here](https://drive.google.com/file/d/1-6kfN_hTaKvKyiYRvQWcIYdhWlODwTJq/view?usp=sharing)

## Models Used
1- Macine Learning Models : SGDClassifier , LinearSVC , MultinomialNB
2-Deep Learning Model :Transformer:Marbert

## Conclusion & Results:
Evaluation Metric: we used overall accuracy and F1 score.

| Model | Metric | Value |
| --- | --- |--- |
| `SGDClassifier` |`F1 SCORE`| 0.46 |
| `LinearSVC` | `F1 SCORE` | 0.55 |
| `MultinomialNB` | `F1 SCORE` | 0.34 |
| `Marbert` | `F1 SCORE` | 0.60 |


## Acknowledgements

 - [QADI Paper](https://arxiv.org/pdf/2005.06557.pdf)
 
 



    
