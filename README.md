# Facts in CrourView Generation 论文

- Interpretable Charge Predictions for Criminal Cases: Learning to Generate Court Views from Fact Descriptions
  - 针对特定的charge，因此输入中包含一个对charge的编码
  - 使用简单的基于注意力的encoder-decoder结构生成rationale
- C3VG
  - 分开了Adj（与判别罪名相关的部分）与Sec（与判断刑期相关的部分）
  - 两个阶段
    - Extraction：从事实描述中抽取出Adj与Sec
    - Generation：生成对应的rationale
    - 加入一个罪名预测任务，降低Adj部分的噪音
  - 数据集很有价值，规模大
- <font color="blue">Explainable legal case matching via inverse optimal transport-based rationale extraction</font>
- How Does NLP Benefit Legal System: A Summary of Legal Artificial Intelligence
  - NLP + Legal 综述
  - 分析了两大类任务
    - 基于符号的任务和方法，主要指生成一个结构化的信息
    - 基于Embedding的方法，指神经网络、预训练等方法，以及法律知识图
  - 分析了三类应用
    - 司法预测
    - 类案匹配
    - 司法问答


