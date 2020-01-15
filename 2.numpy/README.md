## Numpy简介

Numpy是一个用python实现的科学计算的扩展程序库，包括：

- 1、一个强大的N维数组对象Array；
- 2、比较成熟的（广播）函数库；
- 3、用于整合C/C++和Fortran代码的工具包；
- 4、实用的线性代数、傅里叶变换和随机数生成函数。numpy和稀疏矩阵运算包scipy配合使用更加方便。

NumPy（Numeric Python）提供了许多高级的数值编程工具，如：矩阵数据类型、矢量处理，以及精密的运算库。专为进行严格的数字处理而产生。多为很多大型金融公司使用，以及核心的科学计算组织如：Lawrence Livermore，NASA用其处理一些本来使用C++，Fortran或Matlab等所做的任务。

## 一、适合初学者快速入门的Numpy实战全集

本文由光城同学整理

### 本文目录
​      1.Numpy基本操作

 - 1.1 列表转为矩阵
 - 1.2 维度
 - 1.3 行数和列数()
 - 1.4 元素个数

   2.Numpy创建array
 - 2.1 一维array创建
 - 2.2 多维array创建
 - 2.3 创建全零数组
 - 2.4 创建全1数据
 - 2.5 创建全空数组
 - 2.6 创建连续数组
 - 2.7 reshape操作
 - 2.8 创建连续型数据
 - 2.9 linspace的reshape操作

   3.Numpy基本运算
 - 3.1 一维矩阵运算
 - 3.2 多维矩阵运算
 - 3.3 基本计算

   4.Numpy索引与切片

   5.Numpy array合并
 - 5.1 数组合并
 - 5.2 数组转置为矩阵
 - 5.3 多个矩阵合并
 - 5.4 合并例子2

   6.Numpy array分割
 - 6.1 构造3行4列矩阵
 - 6.2 等量分割
 - 6.3 不等量分割
 - 6.4 其他的分割方式

   7.Numpy copy与 =
 - 7.1 =赋值方式会带有关联性
 - 7.2 copy()赋值方式没有关联性

   8.广播机制

   9.常用函数
   
## 二、Numpy练习题100题-提高你的数据分析技能
本文总结了Numpy的常用操作，并做成练习题，练习题附答案建议读者把练习题完成。作者认为，做完练习题，Numpy的基本操作没有问题了，以后碰到问题也可以查这些习题。

网上可以搜到大量的Numpy教程和官方文档，但没有简单的方法来练习。教程是很好的资源，但要付诸实践。 只有实践，才能更好的加深学习。

本站从github搜索到了一些Numpy的练习题100题，含答案，并进行整理：

原代码作者：**Nicolas P. Rougier**（https://github.com/rougier/numpy-100）

**本练习代码可以在github下载：**

[numpy-100](numpy-100)

**使用方法**
文件夹有三个不同的ipynb文件:

- **100_Numpy_exercises_no_solution.ipynb** 

没有答案代码的文件，这个是你做的练习

- **100_Numpy_exercises_with_hint.ipynb**

没有答案代码的文件，但有提示，这个你也可以用来练习

- **100_Numpy_exercises.ipynb**

有答案代码和注释的文件

你可以在**100_Numpy_exercises_no_solution.ipynb** 里输入代码，看看运行结果是否和**100_Numpy_exercises.ipynb** 里面的内容一致。