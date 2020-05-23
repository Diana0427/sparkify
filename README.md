# Sparkify Project

### 背景
本文中的项目是优达学城的毕业项目。数据是一家虚拟的音乐服务商——Sparkify（类似网易云音乐）的用户日志记录。在这个项目中，我先在本地对子数据集（128MB）做了探索性分析和建模，建模时，在分类算法中选择 Logistic Regression、Gradient Boosted Tree 和 Random Forest 建模。然后，在 IBM 云上对中等数据集，使用Gradient Boosted Tree 算法建模。

### 依赖的库
Python 3, Pyspark, datetime, numpy, pandas, matplotlib, seaborn

### 文件
- Sparkify-mini_data.ipynb：在本地对子数据集的探索分析和建模
- Sparkify.ipynb：在 IBM 云上对中等数据集的建模
- Sparkify.html：上面文件的网页格式

### 结论
该项目最后的模型显示，影响用户流失的最重要的3个特征是：用户平均每个 session 听多少首歌、用户喜欢的次数和用户的留存时间。机器学习模型可以较好的预测用户流失。在预测流失之后，我们就可以采取相应的预防措施。之后改进的方向有：选择其他特征进入模型；在调参中增加备选的参数范围。

### 博客文章
博客文章地址为：https://mp.weixin.qq.com/s/gcEjY8TLjJSXVlkknidXHA





