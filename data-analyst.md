# 之前的筆記移到這邊

#為何學習這門課程？

此課程將帶你進入數據分析的世界。你將學習如何完成整個數據分析流程，包括：

* 提出問題
* 將數據處理成可以使用的格式，並解決數據格式相關問題
* 研究數據並找到規律，得出你對數據的直覺
* 得出結論和/或作出預測
* 展示分析結果

你還將學習如何使用 Python 庫 NumPy、Pandas，以及使用 Matplotlib 編寫更加清晰、簡練、運行速度更快的代碼。

# 學習計劃

### 第 1 課：數據分析流程

在本課中，你將學習數據分析流程，包括提出問題、整理和探索數據、得出結論和/或進行預測，以及交流你的發現。你將僅使用 Python 完成 Udacity 學生數據分析，盡量不使用其他數據庫。

### 第 2 課：NumPy 和 Pandas 用於 1D 數據

在本課中，你將開始學習使用 NumPy 和 Pandas 來方便數據分析流程。本課重點是適用於一維數據的功能。你將學習如何使用 NumPy 數組、Pandas 序列和矢量運算。

### 第 3 課：NumPy 和 Pandas 用於 2D 數據

本課將繼續學習 NumPy 和 Pandas，但現在的重點是二維數據。你將學習如何使用二維 NumPy 數組和 Pandas DataFrames。你還會學習如何對數據分組以及對多個文件的數據進行整合。

## 先修要求

要學習這門課程，你需要能熟練地使用 Python 語言編程。

你應該熟悉 if 語句、循環、列表、集合和字典。要學習這些概念，請學習[計算機科學入門課程](https://cn.udacity.com/course/intro-to-computer-science--cs101)。

你還應該熟悉類、對像和模塊。要學習這些概念，請學習 [Python 編程基礎課程](https://cn.udacity.com/course/programming-foundations-with-python--ud036)。

# 開始數據分析

接下來的內容分為兩部分：

#### 字典簡介

在學習《數據分析入門》課程之前，你需要對字典有深入了解。如果你決定學習[數據分析師納米學位項目](https://cn.udacity.com/dand/)，你也需要掌握這一知識。關於字典的這部分內容和我們在階段 2 涉及到的部分概念也很相似。

#### 數據分析入門

你將與 Caroline 一起學習《數據分析入門》。這門課程是了解整個數據分析流程的最佳起點。在學習各節課之前，確保你已經了解各節課程的差異，以及相互之間的關系。這門課程還將介紹 Python 庫：NumPy、Pandas 和 Matplotlib，這些庫是用 Python 進行數據分析不可缺少的工具。它們具有各種便利的功能和高效的性能，使數據分析的編程部分輕松了許多！

這門課程需要你搜索和利用文檔。請積極搜索這門課程提到的 Python 庫的文檔：

* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [Matplotlib](http://matplotlib.org/)



那麼，我們開始吧！


#
工具介紹

對於數據分析師最為重要的工具，即 Anaconda 和 Jupyter notebook



# Anaconda

[Anaconda](https://anaconda.org/) 是一個包含數據科學常用包的發行版本。它基於 conda，一個 package 和環境管理器衍生而來。你將使用 conda 創建環境，以便分隔使用不同 Python 版本和/或不同 package 的項目。你還將使用它在環境中安裝、卸載和更新包。通過使用 Anaconda，使我處理數據的過程更加愉快。



[Jupyter notebook](http://jupyter.org/) 是 Web 文檔，能讓你將文本、圖像和代碼全部組合到一個文檔中。它已經成為數據分析的標准環境。notebook 源自 2011 年的 IPython 項目，之後迅速流行起來。在本課程的第二節課中，你將獲得使用 notebook 進行分析工作的經驗。

讓我們繼續課程！首先學習 Anaconda。


# Virtualenv
很多時候我們需要在不同版本的 library version，甚至是不同版本的 python，一般來說在同一台電腦運行不同版本常常會不太順。因此我們使用虛擬環境\(virtual environment\) Virtualenv