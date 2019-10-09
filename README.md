# Indonesian Essay/Short-answer Scoring
This is the repository for my 2nd place solution in [UKARA 1.0 Challenge](https://evalai.cloudcv.org/web/challenges/challenge-page/410/overview). UKARA 1.0 Challenge is an Indonesian automatic essay/short-answer scoring competition held by Universitas Gadjah Mada.  

The solution is essentially a Bi-LSTM with 100D pretrained Indonesian Word2vec embedding trained on a total of 200M word (Wikipedia dump, Opensubs, and preprocessed UKARA dataset).  

The notebooks was originally run on a Kaggle kernel. To run locally, you need to change some directory variable.  

Result:  
| Type of Data | F1 Score | Precision | Recall |
| ------ | ------ | ------ | ------ |
| Data A cross validation | 0.89277 | 0.85238 | 0.93717 |
| Data B cross validation | 0.77083 | 0.68519 | 0.88095 |
| *Final leaderboard result* | 0.81 | 0.75 | 0.89 |

Links: 
* [Technical report](https://github.com/ilhamfp/ukara-1.0-challenge/blob/master/docs/Indonesian%20Essay%20Scoring%20using%20Bi-LSTM%20with%20Word%20Embedding%20Representation.pdf)
* [Kaggle notebook to produce the Word2vec embedding](https://www.kaggle.com/ilhamfp31/ukara-building-word2vec-100-indonesia)
* [Kaggle dataset containing the Word2vec embedding](https://www.kaggle.com/ilhamfp31/word2vec-100-indonesian)
* [UKARA 1.0 challenge final leaderboard](https://evalai.cloudcv.org/web/challenges/challenge-page/410/leaderboard/1141)
