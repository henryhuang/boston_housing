# 模型评估与验证
## 波士顿房价预测

项目使用 `jupyter notebook (ipython notebook)` 进行展示。

`Github` 加载 `.ipynb` 的速度较慢，建议在 [Nbviewer](http://nbviewer.jupyter.org/github/longcd/boston_housing/blob/master/boston_housing.ipynb) 中查看该项目。

----

### 准备工作

这个项目需要安装**Python 3.5.2**和以下的Python函数库：

- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

你还需要安装一个软件，以运行和编辑[ipynb](http://jupyter.org/)文件。

推荐安装 [Anaconda](https://www.continuum.io/downloads)，这是一个常用的Python集成编译环境，且已包含了本项目中所需的全部函数库。

### 运行

在终端或命令行窗口中，选定`boston_housing/`的目录下（包含此README文件），运行下方的命令：

```jupyter notebook boston_housing.ipynb```

这样就能够启动jupyter notebook软件，并在你的浏览器中打开文件。

### 数据


本项目中使用的数据均包含在scikit-learn数据库([`sklearn.datasets.load_boston`](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html#sklearn.datasets.load_boston))中，你无需额外下载。关于数据的更多信息，你可以访问[UCI机器学习库](https://archive.ics.uci.edu/ml/datasets/Housing)。
