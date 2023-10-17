![Static Badge](https://img.shields.io/badge/mode-practice-blue) ![Static Badge](https://img.shields.io/badge/lang-python-yellow) ![Static Badge](https://img.shields.io/badge/sector-NLP-blue)

## Performance Evaluation of BERT Cased/Uncased Pretrained Models for Spam Classification

### Abstract

BERT is a state-of-the-art language model that has been used for many NLP tasks. In this project, we evaluate the performance of BERT cased/uncased pretrained models for spam classification. We use the Email Spam Collection Dataset from Kaggle. We fine-tune the pretrained models using the dataset and compare the performance of the models. We find that the BERT cased model performs better than the BERT uncased model and the other machine learning models.

### Dataset

The dataset used for this project is the [Email Spam Collection Dataset](https://www.kaggle.com/datasets/abdallahwagih/spam-emails) from Kaggle.

### Requirements
- Python 3.6+
- Tensorflow 2.0+
- Tensorflow Hub 0.7.0+

### Models
- [bert_en_uncased_L-12_H-768_A-12](https://tfhub.dev/tensorflow/bert_en_uncased_L-12_H-768_A-12)
- [bert_en_uncased_L-24_H-1024_A-16](https://tfhub.dev/tensorflow/bert_en_uncased_L-24_H-1024_A-16)
- [bert_en_wwm_uncased_L-24_H-1024_A-16](https://tfhub.dev/tensorflow/bert_en_wwm_uncased_L-24_H-1024_A-16)
- [bert_en_cased_L-12_H-768_A-12](https://tfhub.dev/tensorflow/bert_en_cased_L-12_H-768_A-12)
- [bert_en_cased_L-24_H-1024_A-16](https://tfhub.dev/tensorflow/bert_en_cased_L-24_H-1024_A-16)
- [bert_en_wwm_cased_L-24_H-1024_A-16](https://tfhub.dev/tensorflow/bert_en_wwm_cased_L-24_H-1024_A-16)
- [bert_zh_L-12_H-768_A-12](https://tfhub.dev/tensorflow/bert_zh_L-12_H-768_A-12)
- [bert_multi_cased_L-12_H-768_A-12](https://tfhub.dev/tensorflow/bert_multi_cased_L-12_H-768_A-12)

### Evaluation

| model                                | loss   | accuracy | precision | recall |
| ------------------------------------ | ------ | -------- | --------- | ------ |
| bert_en_uncased_L-12_H-768_A-12      | 29.22% | 88.77%   | 87.18%    | 90.91% |
| bert_en_uncased_L-24_H-1024_A-16     | 50.58% | 76.47%   | 79.64%    | 71.12% |
| bert_en_wwm_uncased_L-24_H-1024_A-16 | 28.87% | 89.30%   | 92.49%    | 85.56% |
| bert_en_cased_L-12_H-768_A-12        | 36.53% | 88.77%   | 88.36%    | 89.30% |
| bert_en_cased_L-24_H-1024_A-16       | 45.54% | 75.94%   | 69.32%    | 93.05% |
| bert_en_wwm_cased_L-24_H-1024_A-16   | 40.65% | 81.28%   | 76.23%    | 90.91% |
| bert_zh_L-12_H-768_A-12              | 24.51% | 91.98%   | 93.37%    | 90.37% |
| bert_multi_cased_L-12_H-768_A-12     | 28.74% | 91.71%   | 89.39%    | 94.65% |
