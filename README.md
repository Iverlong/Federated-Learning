# 设备数据样本量差异对联邦学习的影响研究
随着现代人工智能的不断发展，利用联邦学习来解决实际问题的相关技术日益成熟，其应用也越来越广泛。本文探讨了不同设备之间数据样本量的差异对联邦学习的影响，介绍了一种名为CReFF的联邦特征分类器重新训练方法并验证了其有效性。CReFF方法通过优化后的联邦特征重新训练分类器，提高联邦学习的训练效果。本文通过实验得到了如下结论，证实了设备数据样本量差异对联邦学习有负面影响，而CReFF方法相较于传统的联邦学习基本算法FedAvg，能够有效提升训练质量和模型预测准确率，缓解不同设备数据样本量差异的影响；验证了CReFF方法也能有效处理设备数据存在长尾分布和异质性的情况。这一研究成果为解决不同设备数据样本量差异性问题提供了一些有效的实验支撑，并有望在未来发挥重要作用。

With the continuous development of modern artificial intelligence, the technology of using federated learning to solve practical problems is becoming more mature, and its application is becoming more and more widespread. This article discusses the impact on federated learning when there is a difference in the amount of data samples between different devices, and introduces a federated feature classifier retraining method called CReFF, which uses optimized federated features to retrain the classifier, making it produce performance comparable to retraining the classifier with real data. This article conducts experiments to verify the impact of different device data sample volumes on federated learning. The experimental results show that compared with the traditional federated learning basic algorithm FedAvg, the CReFF method can effectively improve the training quality and the accuracy of model prediction, confirming the effectiveness of the CReFF method in improving the impact of different device data sample volumes on federated learning. Further experiments verify the effectiveness of the CReFF method in dealing with the long-tail distribution and heterogeneity of device data. This research achievement provides a new direction for dealing with the problem of different device data sample volumes, and is expected to play an important role in the future.


### 基线实验：每个本地客户端的数据类别平衡且样本数据总量都相等的FedAvg实验

基线实验代码：https://www.kaggle.com/code/iverlong/test1


### 实验二：设备数据样本量存在差异下的FedAvg和CReFF实验

实验二代码：https://www.kaggle.com/code/iverlong/test2


### 实验三：设备数据存在长尾分布和异质性情况下的FedAvg和CReFF实验

实验三代码：https://www.kaggle.com/code/iverlong/test3
