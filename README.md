# 面试记录

### 阿里妈妈定向算法（挂）
#### 一面 2020/2/23
1. 自我介绍；
2. 聊实习项目
  - 不同方法的效果比较；
  - 项目最后有没有上线；
  - 为什么用JS散度而不是KL散度，有什么优势；
3. 说一个自己最感兴趣的实验室项目
  - 社交关系会使用户的态度趋向一致的假设是否成立；
  - 数据的长尾效应;
  - 遇到的难点，采用什么方法解决的；
4. 算法题：判断链表是否有环，如何确定环的入口,并且数学证明。

### 美团NLP中心（挂）
#### 一面 2020/2/25
1. 聊实习项目
  - 为什么考虑用GCN，有没有用GAT之类的。
2. 算法题：二叉树前序遍历非递归写法。
#### 二面 2020/2/25
1. 自我介绍；
2. 聊项目
  - 项目上线之后有没有评价指标，比如用户点击率（CTR）；
  - 用为什么用深度学习的方法做测评任务。

### 阿里巴巴CBU
#### 一面 2020/2/26
1. 自我介绍；
2. 聊实习项目
  - 问文摘的生成式模型，point generator，如何解决词重复，如何解决oov；
  - word2vec的负采样；
  - 问GCN在推荐领域的用法有没有了解。出了一个情景题，知道用户点击的商品序列，如何用GCN预测用户点击的下一个商品；
  - 问SVM，RF，GDBT的优缺点，GDBT如果过拟合，该怎么办；
  - 为什么LSTM在项目中比CNN效果差；
3. 算法题：寻找两个链表的公共部分起点

说实习生过去主要是负责算法创新。。。

### 字节跳动（挂）
#### 一面 2020/3/3
1. 自我介绍；
2. 聊实习项目
  - 解释TF-IDF，为什么计算IDF时用log；
  - 为什么把CNN用到自然语言处理，和DNN比有什么优势；
  - AUC曲线。
3. 算法题：
  - 1.返回二叉搜索树中两个节点的最近公共祖先
  - 2.一个正整数可以拆成其他正整数的和，求这些正整数的最大连乘积（用动态规划）

#### 二面 2020/3/3
1. 自我介绍；
2. 聊实习项目
  - 解释TF-IDF，样本词数少的时候出现每个词的TF-IDF值都很高的情况怎么办，是否了解其他词袋模型；
  - word2vec的层次softmax为什么概率是1；
  - F1值的优点；
  - AUC曲线。
3. 算法题：
  - 1.求一棵树从根节点到叶子节点路径组成的数字的和
  - 2.给定一个有序数组和一个数k，求k出现的次数（用二分查找，找第一次出现k之后，再二分查找最大的比k小的数和最小的比k大的数）

#### 三面 2020/3/3
1. 自我介绍；
2. 聊实习项目
  - L1正则化为什么可以产生稀疏权重；
  - RNN和DNN相比梯度回传有什么区别。
3. 算法题：给定一个数组，求整数k，使得前k个数和后n-k个数的方差和最小（使用公式D(x)=E(x^2)-E^2(x)，在o(n)复杂度解决）

### 阿里云（挂）
#### 一面 2020/3/8
1. 自我介绍；
2. 聊实习项目
  - 实习过程中最难的是什么？怎么样解决没有反馈这种问题（抽样看效果）；
  - 讲一下LR和SVM的区别，各适用于什么场景，非线性SVM原理；
  - L1、L2正则的作用；
  - 防止过拟合的方法；
  - 卷积和池化的过程；
  - 集成模型bagging和boosting的区别，训练过程有什么不同；
  - 讲一下attention机制（讲了s2q和transformer里的两种attention）；
  - 讲一下优化器；
  - 比较希望从事哪个方向的工作。

### 微软（offer）
#### 一面 2020/3/9
1. 除了简历之外的自我介绍；
2. 聊实习项目
  - 词袋模型；
  - 讲一下词向量模型和原理；
  - 激活函数加或者不加有什么区别；
  - 神经网络层数多少代表什么；
  - 神经网络中防止过拟合的方法；
  - GCN原理；
  - 对未来职业的规划。
3. 算法题：leetcode200岛屿数量

#### 二面 2020/3/12
1. 聊实习项目
  - 视频标题压缩过程中如果抽出来的句子不连贯怎么办；
  - 讲一下LSTM原理，为什么能够解决梯度爆炸和消失问题；
  - 有没有用过Transformer；
  - 讲一下GBDT原理，有没有用过xgboost；
  - 项目中的语料是什么语言的。
2. 算法题：序列化与反序列化二叉树
3. 情景题：设计一个拼音输入法

### 蘑菇街
#### 一面 2020/3/17
1. 算法题：链表L1->L2->...->Ln-1->Ln变成L1->Ln->L2->Ln-1->...
2. 聊实习项目
  - 介绍一下LDA原理；

#### 二面 2020/3/17
1. 介绍实习项目
  - 讲了一下GCN原理，为什么要用GCN。
2. 算法题：求递归计算斐波那契数列的空间和时间复杂度；
3. 情景题：店家有两种商品A和B，第二天发现平均用户点击率比第一天下降，但是A和B各自的用户点击率比第一天上升。问这种情况有没有可能出现，如果不可能出现说明哪里肯定出现了问题，怎么去排查和解决。

### 腾讯微信（挂）
#### 一面 2020/3/19
1. 自我介绍；
2. 聊实习项目
  - TextRank；
  - SVM原理；
  - LSTM结构，为什么能够防止梯度爆炸和消失。
3. 算法题：
  - 反转链表；
  - 正整数字符串转化成字母有多少种结果（1->A, 2->B,...,26-Z）
#### 二面 2020/3/20
1. 自我介绍；
2. 问知识点
  - 双向LSTM原理，最后特征怎么拼接
  - 如何处理不定长数据
  - SVM如何处理线性不可分数据

