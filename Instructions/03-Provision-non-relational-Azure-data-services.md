---
lab:
    title: '实验室 03：预配非关系 Azure 数据服务'
    module: '模块 03：探索 Azure 中的非关系数据'
---

## 说明
在示例场景中，你决定创建以下数据存储：

* Cosmos DB，用于保存有关库存产品数量的信息。你需要存储有关数量级别的当前和历史信息，以便可以跟踪数量随时间变化的方式。每天记录一次数据。
* 用于保存生产和质量数据的 Data Lake store。
* Blob 容器，用于保存公司生产产品的图像。
* 用于共享报告的文件存储。

在此实验室中，你将预配和配置 Cosmos DB 帐户，并通过创建一个数据库、一个容器和一个示例文档来测试它。你还将预配一个 Azure 存储帐户，该帐户可以提供 Blob、文件和 Data Lake 存储。

1.	转到 Microsoft Learn 练习 https://aka.ms/dp900lab03-chs 并在浏览器中完成单元： 
