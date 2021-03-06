# LEAF A Benchmark for Federated Settings

---

**URL:** https://arxiv.org/abs/1812.01097v1

**Code:** https://github.com/TalwalkarLab/leaf

**Jnl/Conf:** CoRR 2018

**Rate:** ★★★★☆

---

## 论文简介
随着联邦学习的发展(例如可穿戴设备，移动电话或自动驾驶汽车组成的网络)每一天都会产生大量的数据，大量的数据可以帮助学习模型，
从而改善每个设备上的用户体验。但是，联邦数据的规模和异构性在联邦学习、元学习和多任务学习等研究领域提出了新的挑战。随着机
器学习社区开始应对这些挑战，本篇论文提出了以确保这些领域的开发以实现的基准为基础。本文提出了LEAF，这是一个用于联邦设置中
学习的模块化基准测试框架。

## 创新点总结
1：介绍了数据集框架和non-iid数据集的评价指标
2：一整套开源的联邦学习数据集
3：严格的评估框架
![](../images/bcxiong/LEAF A Benchmark for Federated Settings.png)

## 思路借鉴
1：数据有一个自然的键控生成过程（每一个key指向一个特定的设备或者用户）
2：这些数据是从数千到百万台设备的网络中产生的
3：数据点的数量在设备之间是倾斜的
