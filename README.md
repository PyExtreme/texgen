# texgen
Text Generation using Deep Learning


This is a tutorial on Text Generation using Deep Learning. Text Generation is the art of generating words or sentences which will follow the given input text.
Here, Long Short-term Memory(LSTM) model is used for the purpose which serves a vital role in preserving the context over long period of time.

The scope of this tutorial are as follows:

* Understanding Text Preprocessing
* Understanding Implementation in PyTorch
* Understanding solving NLP problems using Deep Learning
* Understanding the workflow of Sequence Models

Here is a nice tutorial on building models using PyTorch [Link](https://www.kaggle.com/ankitjha/the-ultimate-pytorch-guide)

**The dataset can be downloaded from [here](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews)**

## Model Selection

Here, the feature vectors are passed through an LSTM layer followed by a dense layer. I have chosen a simple model just as a starter to check the performance.
LSTM is composed of input gate, cell, output gate and forget gate. These are responsible for regulating flow of information across timesteps.
An indepth tutorial on LSTM is explained [here](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
![LSTM](https://cdn-images-1.medium.com/max/1600/1*Niu_c_FhGtLuHjrStkB_4Q.png)

