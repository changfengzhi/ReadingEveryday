第11章 特征选择与稀疏学习
11.1 子集搜索与评价
特征包含相关特征与无关特征。特征也包含冗余特征，冗余特征属于中间概念，有时候可以去掉，有时候又会使学习任务变得更容易，本节暂不讨论。
如果说对所有的子集都进行评估，这样就会导致评估量过大。
这里采用贪心策略，具体可分为前向搜索，后向搜索与双向搜索。
通过信息熵计算信息增益，就可以选出所需的特征子集。
11.2 过滤式选择
过滤式选择先进行特征选择，然后进行训练。
这个relief并不难理解，如果我的一个属性使得样本被分类的更差了，那么就应该减小这个属性的权重。
11.3 包裹式选择
包裹式选择，是将学习器性能作为评价准则。

p252