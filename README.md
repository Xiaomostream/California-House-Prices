# California-House-Prices
Only For Studying DL &amp; Kaggle
https://www.kaggle.com/competitions/california-house-prices

## 任务
![image](https://github.com/user-attachments/assets/16a1cb13-2a78-42a9-aad7-38960d1b986a)

根据房屋信息预测房屋销售价格，房屋信息有多达40种，例如卧室 、生活区域、位置、附近的学校和卖家的广告。

给定数据集：  来自2020 年在加利福尼亚州售出的房屋最后需要提交一个submiss.csv文件

## 数据集处理(特征工程)
- 原始数据并不能直接拿来训练，会存在一些问题
- 存在一些缺失值与异常值 (如何对这些值进行处理)
- 房子的ID与Sold_Price是否可以作为训练的特征
- 数据分为 num_data(数值型) 与 object_data(文本类型)
- 对于日期类型(2019-08-05)的直接按照文本特征进行训练是否合适
- 是否可以直接对所有特征进行训练
### 文本-独热编码
![image](https://github.com/user-attachments/assets/4d5121d2-c700-4a0b-b846-d2d95e9396a4)
### 数字-相关性分析
![image](https://github.com/user-attachments/assets/5cb9ba2e-469b-4854-a320-1ae4771da7ce)

## 模型构建
建立MLP模型
![image](https://github.com/user-attachments/assets/533d9dfb-b78d-49ca-811e-d219a1e30297)

## 模型训练与预测
![image](https://github.com/user-attachments/assets/a9564f4e-6d18-4fbc-aa96-458350be9eaa)

## 生成submission.csv提交
![image](https://github.com/user-attachments/assets/c171933c-cde4-4160-a1db-54c034d145a6)

## 竞赛结果分析

![image](https://github.com/user-attachments/assets/6942a714-c371-422c-b310-b1b56708c768)
![image](https://github.com/user-attachments/assets/8bf1904d-8f81-4f76-a4ae-90971be5d963)
![image](https://github.com/user-attachments/assets/944d8631-5aac-4752-905a-aab339931e5c)




![image](https://github.com/user-attachments/assets/22abd57a-10a0-4211-84ff-a1ceeeb742e2)
