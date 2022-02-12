# TREC Question Classification - PyTorch
## Description
Classification of questions into 5 classes.
The five classes are as follows : 

- ```HUM``` for questions about humans
- ```ENTY``` for questions about entities
- ```DESC``` for questions asking you for a description
- ```NUM``` for questions where the answer is numerical
- ```LOC``` for questions where the answer is a location
- ```ABBR``` for questions asking about abbreviations

*Concepts*
1. RNN
2. LSTM
3. Word Embeddings
4. Multilayer and Bi-Directional RNNs

**RESULTS**

Trained for 5 epochs on Kaggle.
Test Accuracy of ~91%
Model is confused between Entity questions and questions about humans.


### Dataset

[TREC-6](https://torchtext.readthedocs.io/en/latest/datasets.html)

## This project in PyTorch
### Requirements:
- PyTorch
- Torchtext (Used ```torchtext.legacy```)
- Spacy

### Usage

- You can pretrain the model
- You can use the predict_classes function to try your own questions.

### Acknowledgements 

Thanks to the author of  [this](https://github.com/bentrevett/pytorch-sentiment-analysis) for this amazing repo and its explanation and help.




