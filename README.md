# Udacity-Sparkify-project
It is the datamining project for predicting user lost for Sparkify music platform
## 安装
这个项目将使用如下软件和插件：
Anaconda 
Python
PySpark
pandas
Matplotlib
Seaborn
需要在Jupyter Notebook中运行
## 数据集

## 项目概览
   Sparkify是一个国外的音乐平台，本文将介绍预测Sparkify流失用户的过程。我们使用的数据是Sparkify的用户使用log，其中包含用户听的歌曲，时长，艺术家，访问页面，注册时间，地区等等数据，完整的数据集有12G，但因本文是使用单节点Spark来进行数据分析和建模的实验，为了加快速度仅使用其中一部分128M的数据。
 数据集来源于Udacity，完整的数据集大小为12GB。本项目基于完整数据集的一个子集，大小为231MB，预测哪些用户从会员降级为免费，或者直接取消服务了。如果在用户离开之前，可以精确识别到这些用户，sparkify可以通过给用户打折或者其他激励方式留住用户，这样就可以挽救数百位的营业额。

## 文件描述
Sparkify-zh.ipynb 项目的Notebook文件，可在jupyter notebook中执行，必须安装相应包和数据集mini_sparkify_event_data.json
Sparkify-zh.html 此项目的Notebook静态HTML文件 

## 结论
由于使用的是迷你数据集，可能不能反映真实情况。这里SVM的效果最好，逻辑回归泛化性最好，最重要的特征是点踩数ThumbsDowns

## 博客
我写了一篇关于此项目的博客在https://blog.csdn.net/qq_22573293/article/details/109376166

Licensing, Authors, Acknowledgements
此项目的代码等等可以用于任何地方，除了最为Udacity或任何类似项目的作业。
