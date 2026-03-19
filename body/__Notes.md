
## 统计基础

- 搬书匠-5059-Probability and Statistics for Machine Learning-2024-英文版.pdf 
- Introduction to Statistics
  - https://onlinestatbook.com/Online_Statistics_Education.pdf
  - https://onlinestatbook.com/
  - https://onlinestatbook.com/2/introduction/inferential.html
- Statistical Rethinking   https://xcelab.net/rm/
- https://gedeck.github.io/mistat-code-solutions/ModernStatistics/


## Bayes

- Peter D. HoffA First Course in Bayesian Statistical Methods  
  - https://sites.math.rutgers.edu/~zeilberg/EM20/Hoff.pdf
- Bayesian Data Analysis course - Demos
  - https://avehtari.github.io/BDA_course_Aalto/demos.html#BDA_Python_demos


## 因果推断
- https://d2cml-ai.github.io/
  - https://github.com/d2cml-ai/Data-Science-Python/tree/main

## 数据分析概览

![20250919160021](https://fig-lianxh.oss-cn-shenzhen.aliyuncs.com/20250919160021.png)

> Source: <https://github.com/MoinDalvs/Learn_Feature_Engineering>

- EDA excercise
  - [Retail-Marketing-Exploratory-Data-Analysis-and-Data-Preprocessing](https://github.com/simrann20/Retail-Marketing-Exploratory-Data-Analysis-and-Data-Preprocessing/blob/main/Python_ProjectNo2.ipynb) 

## 金融理论

- file:///D:/Rbook/dslian-R/refs/Ang_2021_Analyzing_Financial_Data_Using_R.pdf#page=200.09
- [Yves_Hilpisch]_Python_for_Finance_－_Analyze_Big_Financial_Data.pdf 
  - 最优化方法等；积分

## Python 基础

- 参考「2478-Python 101 2nd Edition-2020-英文版.pdf」
  - 写的非常细致


## 数据来源

- Kaggle
- 阿里云天池
  - [抖音电商用户特征](https://tianchi.aliyun.com/dataset/204698)
  - [天猫复购预测Baseline](https://tianchi.aliyun.com/dataset/187161)
  - [电商购物用户行为分析数据](https://tianchi.aliyun.com/dataset/203653)
  - [淘宝用户行为可视化](https://tianchi.aliyun.com/dataset/202033)
    - 9.9w 条数据；支付方式，购物金额等
  - [金融守护者：金融风险预测学习赛](https://tianchi.aliyun.com/competition/entrance/531830/information)
    - 三个数据文件，共 200M
    - 赛题以预测用户贷款是否违约为任务。该数据来自某信贷平台的贷款记录，总数据量超过120w，包含47列变量信息，其中15列为匿名变量。为了保证比赛的公平性，将会从中抽取80万条作为训练集，20万条作为测试集A，20万条作为测试集B，同时会对employmentTitle、purpose、postCode和title等信息进行脱敏。
  - [银行客户认购产品预测](https://tianchi.aliyun.com/competition/entrance/531993/information)
    - Data: 3M 
    - 赛题以银行产品认购预测为背景，想让你来预测下客户是否会购买银行的产品。在和客户沟通的过程中，我们记录了和客户联系的次数，上一次联系的时长，上一次联系的时间间隔，同时在银行系统中我们保存了客户的基本信息，包括：年龄、职业、婚姻、之前是否有违约、是否有房贷等信息，此外我们还统计了当前市场的情况：就业、消费信息、银行同业拆解率等。
  - [中文NLP地址要素解析](https://tianchi.aliyun.com/competition/entrance/531900/information)
    - 中文地址要素解析任务的目标即将一条地址分解为上述几个部分的详细标签，如：
      ```
      输入：浙江省杭州市余杭区五常街道文一西路969号淘宝城5号楼，放前台
      输出：
      Province=浙江省 city=杭州市 district=余杭区 town=五常街道 
      road=文一西路road_number=969号 poi=淘宝城 
      house_number=5号楼 other=，放前台
      ```

## 文本分析

### TED 演讲数据
- [TED talks](https://github.com/Chando0185/Multiverse_of_100-_data_science_project_series/tree/main/TED%20Talk)
  - 记录 4467 条 TED 演讲的相关信息。
  - 共三份数据 (约 15 MB)：
    - `tags_dataset.csv`：包含了每场演讲的标签信息，每条数据包含 `ID` 和 `标签` 两个变量。同一个 ID 下有 5-7 个 Tags
    - `tedx_dataset.csv`：包含了每场演讲的相关信息，记录了 4467 条数据，每条数据包含 `ID`、`演讲者`、`标题`、`详情`、`发布时间`、`URL`、`观看次数` 七个变量。
    - `watch_next_dataset.csv`：用户观看的下一个 TED 演讲的 URL 和 IDs。
      - 共 77364 条记录。每个 ID 可能对应多个 URL 和 IDs，表示用户在观看了某个 TED 演讲后，接下来观看了哪些 TED 演讲。数值从 5-30 个不等。


