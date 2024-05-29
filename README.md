# 设备数据样本量差异对联邦学习的影响研究
随着现代人工智能的不断发展，利用联邦学习来解决实际问题的相关技术日益成熟，其应用也越来越广泛。本文探讨了不同设备之间数据样本量的差异对联邦学习的影响，介绍了一种名为CReFF的联邦特征分类器重新训练方法并验证了其有效性。CReFF方法通过优化后的联邦特征重新训练分类器，提高联邦学习的训练效果。本文通过实验得到了如下结论，证实了设备数据样本量差异对联邦学习有负面影响，而CReFF方法相较于传统的联邦学习基本算法FedAvg，能够有效提升训练质量和模型预测准确率，缓解不同设备数据样本量差异的影响；验证了CReFF方法也能有效处理设备数据存在长尾分布和异质性的情况。这一研究成果为解决不同设备数据样本量差异性问题提供了一些有效的实验支撑，并有望在未来发挥重要作用。

As modern artificial intelligence continues to advance, the use of federated learning to address practical problems has become increasingly mature, and its applications are becoming more widespread. This article explores the impact of varying data sample sizes across different devices on federated learning, and introduced a method called Classifier Re-training with Federated Features (CReFF) and validated its effectiveness. The CReFF approach improves training quality and model prediction accuracy in federated learning by optimizing retrained federated features. The study confirms that differences in device data sample sizes negatively affect federated learning, and CReFF outperforms the traditional federated learning baseline algorithm, FedAvg, mitigating the impact of varying device data sample sizes. Additionally, CReFF demonstrates effectiveness in handling long-tail distributions and heterogeneity in device data. This research provides valuable experimental support for addressing the challenge of disparate device data sample sizes and holds promise for future applications.


### 基线实验：每个本地客户端的数据类别平衡且样本数据总量都相等的FedAvg实验

基线实验代码：https://www.kaggle.com/code/iverlong/test1


### 实验二：设备数据样本量存在差异下的FedAvg和CReFF实验

实验二代码：https://www.kaggle.com/code/iverlong/test2


### 实验三：设备数据存在长尾分布和异质性情况下的FedAvg和CReFF实验

实验三代码：https://www.kaggle.com/code/iverlong/test3
