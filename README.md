# 余弦相似度算法
**余弦相似度**，又称为余弦相似性，是通过计算两个<font color = blue>向量</font>的夹角<font color=blue>余弦</font>值，
来评估他们的相似度。 余弦相似度将向量根据坐标值，绘制到向量空间中，如常见的二维空间。

余弦相似度衡量的是2个向量间的夹角大小，通过夹角的余弦值表示结果，因此2个向量的余弦相似度为：

计算公示：分子为向量A与向量B的点乘，父母为各自的L2相乘，即将所有维度值的平方相加后开方。

<font color = blue>余弦相似度的取值为\[-1,1\]，值越大表示越相似</font>


# 调整余弦相似度
余弦相似度更多的是从方向上区分差异，但是对绝对的数值是不敏感的。

余弦相似度对数值的不敏感导致了结果的误差，需要修正这种不合理性，就出现了调整余弦相似度，即所有维度上的数值都减去一个均值