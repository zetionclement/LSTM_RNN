## 在PTB数据集上使用循环神经网络实现语言建模

#### 运行环境：Windows 10  TensorFlow-gpu 1.11

#### 搭建一个两层深的循环神经网络，每一层有200个LSTM结构，两层神经网络间设置Dropout。

#### 总共训练13个Epoch，权重初始值为0.1，学习速率初始值为1.0，4个Epoch后开始对学习率进行调整，学习衰减率为0.5，batch_size设置为20，num_steps设置为20。

#### 13个Epoch后，在测试集上的perplexity为115.368。

#### 运行方法：首先打开LSTM_RNN.py文件，把第169行的PTB路径设置为自己PTB文件的路径，然后运行python LSTM_RNN.py。


#### 运行过程截图
![](https://github.com/zetionclement/LSTM_RNN/blob/master/LSTM_RNN%E6%88%AA%E5%9B%BE.png)
