## Targeted Sentiment Analysis On Turkish Texts

Sentiment analysis is a technique used to determine the sentiment expressed in a piece of text, often categorized as positive, negative, or neutral. **Targeted sentiment analysis** extends this concept by focusing on the sentiment associated with a specific target, such as a brand or a product, within a given text.

Inspired by [this paper]([https://aclanthology.org/2022.acl-srw.39/](https://aclanthology.org/2022.acl-srw.39/)), this project aims to develop a targeted sentiment analysis model for Turkish texts by fine-tuning the BERTurk model, a pre-trained language model tailored for the Turkish language, using a dataset consisting of tweets about six different brands, each labeled with sentence-level and targeted sentiment information. 

This repository houses the training codes for the three models outlined in the aforementioned paper: A **baseline model**, **T-BERT** and **T-BERT_marked**. 

Training codes for other two models, **T-BERT_marked-MP** and  **T-BERT_marked-TS**, mentioned in the paper is not included.

Trainings are performed in Google Colab environment.

- Information about the dataset can be found [here](https://github.com/palahb/turkish-tsa-dataset).
- An API for using a model developed by these training codes can be found [here](https://github.com/palahb/turkish-tsa-public).
- Please check Turkish Language Processing Platform of Computer Engineering Department of Boğaziçi University ([TULAP](https://tulap.cmpe.boun.edu.tr/)) for more info. A demo tool using a model trained by these notebooks can be found [here](https://tulap.cmpe.boun.edu.tr/demo/targeted-sentiment-analysis).

Special thanks to Prof. Arzucan Özgür and Mustafa Melih Mutlu.