# beautifulNLP
### 命名实体识别

|     模型名称     |   使用框架    |
| :--------------: | :-----------: |
|     Bi-LSTM      | TensorFlow1.x |
|   Bi-LSTM-CRF    | TensorFlow1.x |
|    ID-CNN-CRF    | TensorFlow1.x |
| BERT-Bi-LSTM-CRF | TensorFlow1.x |
|       HMM        |       -       |

### 语言模型

|    模型名称     |                     使用框架                     |
| :-------------: | :----------------------------------------------: |
|     one-hot     |                        -                         |
| tf-idf-sentence |                        -                         |
|    word2vec     |                      Gensim                      |
|      glove      | [官方源码](https://github.com/stanfordnlp/GloVe) |
|     n-gram      |                        -                         |

### 文本分类

|       模型名称        |    使用框架    |
| :-------------------: | :------------: |
| Naive Bayesian 二分类 |  Scikit-Learn  |
|      RNN 二分类       | TensorFlow1.x  |
| Bert-baseline 多分类  |    Pytorch     |
|    TextRNN 多分类     | TensorFlow 2.x |
|    TextCNN 多分类     | TensorFlow 2.x |

### 文本摘要

|   模型名称   | 使用框架 |
| :----------: | :------: |
| TextRank-MMR |  Jieba   |

### 资料整理

- 停用词文件
- 逻辑回归