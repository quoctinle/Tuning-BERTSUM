# Extractive Text Summarization using Fine-Tune BERT
**The re-implementation of the baseline "Fine-Tune BERT for Extractive Summarization (Y. Liu et al., 2019)".**

Results of the baseline model on the CNN/Dailymail (25/3/2019):

|  Models| ROUGE-1 | ROUGE-2 |ROUGE-L
| :---         |     :---      |         :--- |          :--- |
| Transformer Baseline   | 40.9     | 18.02    |37.17    |
| BERTSUM+Classifier     | 43.23       | 20.22    |39.60      |
| BERTSUM+Transformer     | 43.25      | 20.24    |39.63     |
| BERTSUM+LSTM     | 43.22       |  20.17    |39.59      |

