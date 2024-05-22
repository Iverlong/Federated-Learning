# 设备数据样本量差异对联邦学习的影响研究
随着现代人工智能的不断发展，利用联邦学习来解决实际问题的相关技术日益成熟，其应用也越来越广泛。本文探讨了当不同设备之间数据样本量存在差异时对联邦学习的影响，并引入了一种名为CReFF的联邦特征分类器重新训练方法，利用优化后的联邦特征来重新训练分类器，使其产生与通过真实数据重新训练分类器相当的性能。本文进行了实验验证设备数据样本量不同对联邦学习的影响，实验结果表明，相较于传统的联邦学习基本算法FedAvg，CReFF方法能有效提升训练质量和模型预测的准确率，证实了CReFF方法在改善不同设备数据样本量存在差异时对联邦学习的影响上的有效性。进一步实验验证了CReFF方法在处理设备数据存在长尾分布和异质性情况下的有效性。这一研究成果为应对不同设备数据样本量差异性问题提供了新的方向，有望在未来发挥重要的作用。

With the continuous development of modern artificial intelligence, the technology of using federated learning to solve practical problems is becoming more mature, and its application is becoming more and more widespread. This article discusses the impact on federated learning when there is a difference in the amount of data samples between different devices, and introduces a federated feature classifier retraining method called CReFF, which uses optimized federated features to retrain the classifier, making it produce performance comparable to retraining the classifier with real data. This article conducts experiments to verify the impact of different device data sample volumes on federated learning. The experimental results show that compared with the traditional federated learning basic algorithm FedAvg, the CReFF method can effectively improve the training quality and the accuracy of model prediction, confirming the effectiveness of the CReFF method in improving the impact of different device data sample volumes on federated learning. Further experiments verify the effectiveness of the CReFF method in dealing with the long-tail distribution and heterogeneity of device data. This research achievement provides a new direction for dealing with the problem of different device data sample volumes, and is expected to play an important role in the future.


### 基线实验：每个本地客户端中数据类别平衡且样本数据总量都相等的FedAvg实验

基线实验代码：https://www.kaggle.com/code/iverlong/test1


### 实验二：设备数据样本量存在差异下的FedAvg和CReFF实验

实验二代码：https://www.kaggle.com/code/iverlong/test2


### 实验三：设备数据存在长尾分布和异质性情况下的FedAvg和CReFF实验

实验三代码：https://www.kaggle.com/code/iverlong/test3
