Task1：Introduction to word vectors
----------

### 00_背景
自然语言处理作为人工智能实现技术的重要组成部分，近年来随着深度学习发展使得自然语言有了新的方法。为了能够让语言能够输入到深度学习的算法中需要对每个词进行向量化。

### 01_相关工作

NLP一般处理过程为
![Image text](https://raw.githubusercontent.com/xiaohan2013/nlp-resources/master/cs224n-notes/nlp.png)

在整个流程中，语言模型的使用决定了特征工程的词的表示和句子的表示方式。

语言模型（Language Model）可以词表示和单词序列概率表示。语言模型（Language Model，LM），给出一句话的前k个词，希望它可以预测第k+1个词是什么，即给出一个第k+1个词可能出现的概率的分布p(xk+1|x1,x2,...,xk)。


* 语言模型的发展历程
	* 文法规则模型（Automate）在计算机初始阶段，计算机编程语言的 发展归纳出针对自然语言的语法规则。但自然语言本身的多样性、口语化，在时空上演化，以及本身强大的纠错能力，导致了语法规则的急剧膨胀，不可持续；
	* 统计模型（N-Gram）统计语言模型就是计算一个句子的概率大小，整句的概率就是各词出现概率的乘积，概率值越大该句子越合理；
	* 神经网络模型（NNLM）
	* 预训练应用模型
* 语言模型的评价指标—PPL()


### 02_模型


### 03_实验


### 04_总结



### 参考文献
[1] Mikolov T , Chen K , Corrado G , et al. Efficient Estimation of Word Representations in Vector Space[J]. Computer ence, 2013.
