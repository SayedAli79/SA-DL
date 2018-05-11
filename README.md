# IMPORTANT

**This repo is no longer maintained! Please go to: <https://github.com/songyouwei/ABSA-PyTorch>**

# SA-DL

> Sentiment Analysis with Deep Learning models. Implemented with Tensorflow and Keras.
>
> 使用深度学习模型解决情感分析问题。

![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg) ![PRsWelcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg) ![PythonVersion](https://img.shields.io/pypi/pyversions/Django.svg)

## Dependencies

* Tensorflow 1.7
* Python 3.6
* Pre-trained word vectors (See `utils.py` for more detail)
  * Download pre-trained Twitter word vectors [here](https://github.com/stanfordnlp/GloVe#download-pre-trained-word-vectors),
  * extract the [glove.twitter.27B.zip](http://nlp.stanford.edu/data/wordvecs/glove.twitter.27B.zip) and [glove.42B.300d.zip](http://nlp.stanford.edu/data/wordvecs/glove.42B.300d.zip) to the root directory

## An usage example

### Training:

```sh
python ram.py
```

### See the training process

```sh
tensorboard --logdir=./ram_logs
```


## Reviews / Surveys

Zhang, Lei, Shuai Wang, and Bing Liu. "Deep Learning for Sentiment Analysis: A Survey." arXiv preprint arXiv:1801.07883 (2018). [[pdf]](https://arxiv.org/pdf/1801.07883)

Young, Tom, et al. "Recent trends in deep learning based natural language processing." arXiv preprint arXiv:1708.02709 (2017). [[pdf]](https://arxiv.org/pdf/1708.02709)


## Papers & Models

### RAM (ram.py)
Chen, Peng, et al. "Recurrent Attention Network on Memory for Aspect Sentiment Analysis." Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing. 2017. [[pdf]](http://www.aclweb.org/anthology/D17-1047)

![ram](assets/ram.png)


### MemNet (dmn.py)
Tang, Duyu, Bing Qin, and Ting Liu. "Aspect level sentiment classification with deep memory network." arXiv preprint arXiv:1605.08900 (2016). [[pdf]](https://arxiv.org/pdf/1605.08900)

![memnet](assets/memnet.png)


### IAN
Ma, Dehong, et al. "Interactive Attention Networks for Aspect-Level Sentiment Classification." arXiv preprint arXiv:1709.00893 (2017).

![han](assets/han.png)


### TD-LSTM (td_lstm.py)

Tang, Duyu, et al. "Effective LSTMs for Target-Dependent Sentiment Classification." Proceedings of COLING 2016, the 26th International Conference on Computational Linguistics: Technical Papers. 2016. [[pdf]](https://arxiv.org/pdf/1512.01100)

![td-lstm](assets/td-lstm.png)


### LSTM (lstm.py)

![lstm](assets/lstm.png)


## Licence

MIT License