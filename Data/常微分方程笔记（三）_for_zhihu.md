# 常微分方程笔记（三）

本篇笔记将接着笔记（二），继续以《大学数学教程》（第二版）为基础，简单地学习或复习常微分方程的基础知识。第5节的内容可以**类比线性代数**的知识学习。

###  <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 5 线性常微分方程组的一般理论

##### 1. 一阶线性常微分方程组

一般形式

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
y_1'=a_{11}(x)y_1+a_{12}(x)y_2+...+a_{1n}(x)y_n+f_1(x), \\
y_2'=a_{21}(x)y_1+a_{22}(x)y_2+...+a_{2n}(x)y_n+f_2(x), \\
............ \\
y_n'=a_{n1}(x)y_1+a_{n2}(x)y_2+...+a_{nn}(x)y_n+f_n(x). \\
\end{cases}
\tag{1}
" alt="\begin{cases}
y_1'=a_{11}(x)y_1+a_{12}(x)y_2+...+a_{1n}(x)y_n+f_1(x), \\
y_2'=a_{21}(x)y_1+a_{22}(x)y_2+...+a_{2n}(x)y_n+f_2(x), \\
............ \\
y_n'=a_{n1}(x)y_1+a_{n2}(x)y_2+...+a_{nn}(x)y_n+f_n(x). \\
\end{cases}
\tag{1}
" class="ee_img tr_noresize" eeimg="1">
用矩阵表示，引入

<img src="https://www.zhihu.com/equation?tex=y=\left(
 \begin{matrix}
   y_1 \\
   y_2 \\
   \vdots \\
   y_n
  \end{matrix}
  \right),
  A(x)=\left(
  \begin{matrix}
  a_{11}(x)a_{12}(x)\cdots a_{1n}(x) \\
  a_{21}(x)a_{22}(x)\cdots a_{2n}(x) \\
  \cdots \cdots \cdots \cdots \\
  a_{n1}(x)a_{n2}(x)\cdots a_{nn}(x)
  \end{matrix}
  \right),
  f(x)=\left(
 \begin{matrix}
   f_1(x) \\
   f_2(x) \\
   \vdots \\
   f_n(x)
  \end{matrix}
  \right).
  \tag{2}
" alt="y=\left(
 \begin{matrix}
   y_1 \\
   y_2 \\
   \vdots \\
   y_n
  \end{matrix}
  \right),
  A(x)=\left(
  \begin{matrix}
  a_{11}(x)a_{12}(x)\cdots a_{1n}(x) \\
  a_{21}(x)a_{22}(x)\cdots a_{2n}(x) \\
  \cdots \cdots \cdots \cdots \\
  a_{n1}(x)a_{n2}(x)\cdots a_{nn}(x)
  \end{matrix}
  \right),
  f(x)=\left(
 \begin{matrix}
   f_1(x) \\
   f_2(x) \\
   \vdots \\
   f_n(x)
  \end{matrix}
  \right).
  \tag{2}
" class="ee_img tr_noresize" eeimg="1">
从而有

<img src="https://www.zhihu.com/equation?tex=y'=A(x)y+f(x)
\tag{3}
" alt="y'=A(x)y+f(x)
\tag{3}
" class="ee_img tr_noresize" eeimg="1">
 <img src="https://www.zhihu.com/equation?tex=y" alt="y" class="ee_img tr_noresize" eeimg="1"> 是未知的列向量函数， <img src="https://www.zhihu.com/equation?tex=A(x)" alt="A(x)" class="ee_img tr_noresize" eeimg="1"> 是系数矩阵，当 <img src="https://www.zhihu.com/equation?tex=f(x)\neq 0" alt="f(x)\neq 0" class="ee_img tr_noresize" eeimg="1"> 时，（3）为**非齐次线性微分方程组**，当 <img src="https://www.zhihu.com/equation?tex=f(x) \equiv 0" alt="f(x) \equiv 0" class="ee_img tr_noresize" eeimg="1"> 时，则为相应的**齐次线性微分方程组**。

<img src="https://www.zhihu.com/equation?tex=y'=A(x)y
\tag{4}
" alt="y'=A(x)y
\tag{4}
" class="ee_img tr_noresize" eeimg="1">


由笔记（二），当满足 <img src="https://www.zhihu.com/equation?tex=a_{ij}(x),f_i(x)" alt="a_{ij}(x),f_i(x)" class="ee_img tr_noresize" eeimg="1"> 在区间上都连续时，方程组（1）的解是存在且唯一的。

我们仍然从较为简单的齐次方程组入手。

* **齐次线性微分方程组**

  **定理1** 若 <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> 个向量函数是方程组（4）的解，那么它们的**线性组合**也是方程组的解。

  **定义1** 线性相关与线性无关的定义。（为省略篇幅，不过多阐述）

  **定义2** 朗斯基行列式（Wronskian）
  ![62215bb9625c18e932b05d44bb5e0f3](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（三）/62215bb9625c18e932b05d44bb5e0f3.png)

  **定理2** 对于向量函数组 <img src="https://www.zhihu.com/equation?tex=y_1(x),\cdots,y_n(x),x\in I" alt="y_1(x),\cdots,y_n(x),x\in I" class="ee_img tr_noresize" eeimg="1"> ，如果存在某点 <img src="https://www.zhihu.com/equation?tex=x_0 \in I" alt="x_0 \in I" class="ee_img tr_noresize" eeimg="1"> ，使得这个向量组线性无关，那么这个向量函数组也线性无关。（可以用反证法证明）
  也就是说，对于向量组函数来说，只要自变量能取到某一个值使得只有全为零的系数才使得他们的组合为零，整个区间内的函数都是线性无关的。

  **推论1** 对于朗斯基行列式，如果 <img src="https://www.zhihu.com/equation?tex=W(x_0) \neq 0" alt="W(x_0) \neq 0" class="ee_img tr_noresize" eeimg="1"> ，那么构成朗斯基行列式的向量函数组是线性无关的。

  **推论2** 相应的，如果向量函数组 <img src="https://www.zhihu.com/equation?tex=y_1(x),\cdots,y_n(x),x\in I" alt="y_1(x),\cdots,y_n(x),x\in I" class="ee_img tr_noresize" eeimg="1"> 线性相关，那么 <img src="https://www.zhihu.com/equation?tex=W(x) \equiv 0,\forall x\in I" alt="W(x) \equiv 0,\forall x\in I" class="ee_img tr_noresize" eeimg="1"> 。

  **定理3** 如果向量函数 <img src="https://www.zhihu.com/equation?tex=\varphi_1(x),\cdots,\varphi_n(x),x\in I" alt="\varphi_1(x),\cdots,\varphi_n(x),x\in I" class="ee_img tr_noresize" eeimg="1"> ，是齐次方程组（4）的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个解，那么它们在 <img src="https://www.zhihu.com/equation?tex=I" alt="I" class="ee_img tr_noresize" eeimg="1"> 上线性相关的充要条件是 <img src="https://www.zhihu.com/equation?tex=W(x)\equiv 0，\forall x\in I" alt="W(x)\equiv 0，\forall x\in I" class="ee_img tr_noresize" eeimg="1"> 。

  **定理4** 其次线性微分方程组（4）一定存在 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个线性无关的解。

  **定理5** 如果 <img src="https://www.zhihu.com/equation?tex=\varphi_1(x),\cdots,\varphi_n(x),x\in I" alt="\varphi_1(x),\cdots,\varphi_n(x),x\in I" class="ee_img tr_noresize" eeimg="1"> 是方程组（4）的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个线性无关的解，那么（4）的任意一个解都可以表示为 <img src="https://www.zhihu.com/equation?tex=\varphi_1(x),\cdots,\varphi_n(x),x\in I" alt="\varphi_1(x),\cdots,\varphi_n(x),x\in I" class="ee_img tr_noresize" eeimg="1"> 的线性组合

<img src="https://www.zhihu.com/equation?tex=\varphi(x)=c_1\varphi_1(x)+\cdots+c_n\varphi_n(x)
  \tag{5}
  " alt="\varphi(x)=c_1\varphi_1(x)+\cdots+c_n\varphi_n(x)
  \tag{5}
  " class="ee_img tr_noresize" eeimg="1">
  **推论** 从而可以得到**齐次线性微分方程组的通解结构**
  如果 <img src="https://www.zhihu.com/equation?tex=\varphi_1(x),\cdots,\varphi_n(x),x\in I" alt="\varphi_1(x),\cdots,\varphi_n(x),x\in I" class="ee_img tr_noresize" eeimg="1"> 是方程组（4）的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个线性无关的解，那么通解可以写为

<img src="https://www.zhihu.com/equation?tex=y(x)=c_1\varphi_1(x)+\cdots+c_n\varphi_n(x)
  \tag{6}
  " alt="y(x)=c_1\varphi_1(x)+\cdots+c_n\varphi_n(x)
  \tag{6}
  " class="ee_img tr_noresize" eeimg="1">
  其中 <img src="https://www.zhihu.com/equation?tex=c_1,c_2,\cdots,c_n" alt="c_1,c_2,\cdots,c_n" class="ee_img tr_noresize" eeimg="1"> 为 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个独立的常量。
  （4）的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个线性无关解为它的**基本解组**。
  将方程组的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个解排列成一个矩阵

<img src="https://www.zhihu.com/equation?tex=\Phi(x)\equiv (\varphi_1(x),\cdots,\varphi_n(x))=
  \left(
  \begin{matrix}
  \varphi_{11}(x) & \varphi_{12}(x) & \cdots & \varphi_{1n}(x) \\
  \varphi_{21}(x) & \varphi_{22}(x) & \cdots & \varphi_{2n}(x) \\
  \vdots & \vdots & \ddots & \vdots \\
  \varphi_{n1}(x) & \varphi_{n2}(x) & \cdots & \varphi_{nn}(x)
  \end{matrix}
  \right)
  \tag{7}
  " alt="\Phi(x)\equiv (\varphi_1(x),\cdots,\varphi_n(x))=
  \left(
  \begin{matrix}
  \varphi_{11}(x) & \varphi_{12}(x) & \cdots & \varphi_{1n}(x) \\
  \varphi_{21}(x) & \varphi_{22}(x) & \cdots & \varphi_{2n}(x) \\
  \vdots & \vdots & \ddots & \vdots \\
  \varphi_{n1}(x) & \varphi_{n2}(x) & \cdots & \varphi_{nn}(x)
  \end{matrix}
  \right)
  \tag{7}
  " class="ee_img tr_noresize" eeimg="1">
  那么 <img src="https://www.zhihu.com/equation?tex=\Phi(x)" alt="\Phi(x)" class="ee_img tr_noresize" eeimg="1"> 就称之为（4）的一个**解矩阵**。特别的当这些解线性无关时，就为**基本解矩阵**。
  以上的结果都可以再表示：
  （1）  <img src="https://www.zhihu.com/equation?tex=\Phi(x)" alt="\Phi(x)" class="ee_img tr_noresize" eeimg="1"> 是齐次方程组的解矩阵，那么 <img src="https://www.zhihu.com/equation?tex=\Phi(x)C" alt="\Phi(x)C" class="ee_img tr_noresize" eeimg="1"> 也是方程组的解， <img src="https://www.zhihu.com/equation?tex=C" alt="C" class="ee_img tr_noresize" eeimg="1"> 为 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 维常数列向量。

  （2） 方程组一定存在一个基解矩阵  <img src="https://www.zhihu.com/equation?tex=\Phi(x)" alt="\Phi(x)" class="ee_img tr_noresize" eeimg="1"> ，使得任意解 <img src="https://www.zhihu.com/equation?tex=y(x)" alt="y(x)" class="ee_img tr_noresize" eeimg="1"> 都可以表示为 <img src="https://www.zhihu.com/equation?tex=y(x)=\Phi(x)C" alt="y(x)=\Phi(x)C" class="ee_img tr_noresize" eeimg="1"> ，这也是通解。

  （3）   <img src="https://www.zhihu.com/equation?tex=\Phi(x)" alt="\Phi(x)" class="ee_img tr_noresize" eeimg="1"> 是基解矩阵的充要条件是 <img src="https://www.zhihu.com/equation?tex=\det\Phi(x_0)=W(x_0)\neq 0" alt="\det\Phi(x_0)=W(x_0)\neq 0" class="ee_img tr_noresize" eeimg="1"> 。

  （4） 如果  <img src="https://www.zhihu.com/equation?tex=\Phi(x)" alt="\Phi(x)" class="ee_img tr_noresize" eeimg="1"> 是基解矩阵，而 <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> 是一个非奇异常矩阵，那么 <img src="https://www.zhihu.com/equation?tex=\Phi(x)P" alt="\Phi(x)P" class="ee_img tr_noresize" eeimg="1"> 也是一个基解矩阵。

  **定理6** 刘维尔公式（Liouville）
  朗斯基行列式 <img src="https://www.zhihu.com/equation?tex=W(x)=\det\Phi(x)" alt="W(x)=\det\Phi(x)" class="ee_img tr_noresize" eeimg="1"> 满足

<img src="https://www.zhihu.com/equation?tex=W(x)=W(x_0)\exp(\int_{x_0}^x trA(x)dx),x_0\in I
  \tag{8}
  " alt="W(x)=W(x_0)\exp(\int_{x_0}^x trA(x)dx),x_0\in I
  \tag{8}
  " class="ee_img tr_noresize" eeimg="1">
  其中 <img src="https://www.zhihu.com/equation?tex=trA(x)" alt="trA(x)" class="ee_img tr_noresize" eeimg="1"> 表示矩阵 <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> 的迹，为矩阵对角元素之和。
  证明如下
  ![1f7d531216631c8a7800ebec145b0ab](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（三）/1f7d531216631c8a7800ebec145b0ab.png)

  ![7f705ae75e158ef8619681138bc4221](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（三）/7f705ae75e158ef8619681138bc4221.png)

* 非齐次线性方程组

  **定理7** **非齐次线性微分方程组的通解结构**
  设 <img src="https://www.zhihu.com/equation?tex=Y(x)" alt="Y(x)" class="ee_img tr_noresize" eeimg="1"> 是方程组（3）的一个解（特解），其对应的齐次方程组的一个基解矩阵为 <img src="https://www.zhihu.com/equation?tex=\Phi(x)" alt="\Phi(x)" class="ee_img tr_noresize" eeimg="1"> ，那么方程组的任一解可表示为

<img src="https://www.zhihu.com/equation?tex=y=Y_1(x)=\Phi(x)C+Y(x)
  \tag{9}
  " alt="y=Y_1(x)=\Phi(x)C+Y(x)
  \tag{9}
  " class="ee_img tr_noresize" eeimg="1">
  **常数变易法**
  对于齐次方程组（4），设基解矩阵为 <img src="https://www.zhihu.com/equation?tex=\Phi(x)" alt="\Phi(x)" class="ee_img tr_noresize" eeimg="1"> ，那么有 <img src="https://www.zhihu.com/equation?tex=y=\Phi(x)C" alt="y=\Phi(x)C" class="ee_img tr_noresize" eeimg="1"> 。现在利用常数变易法，把待定常数 <img src="https://www.zhihu.com/equation?tex=C" alt="C" class="ee_img tr_noresize" eeimg="1"> 改写为待定函数 <img src="https://www.zhihu.com/equation?tex=C(x)" alt="C(x)" class="ee_img tr_noresize" eeimg="1"> ，那么有

<img src="https://www.zhihu.com/equation?tex=y'=\Phi'(x)C(x)+\Phi(x)C'(x)=A(x)\Phi(x)C(x)+f(x)
  \tag{10}
  " alt="y'=\Phi'(x)C(x)+\Phi(x)C'(x)=A(x)\Phi(x)C(x)+f(x)
  \tag{10}
  " class="ee_img tr_noresize" eeimg="1">
  而 <img src="https://www.zhihu.com/equation?tex=\Phi(x)" alt="\Phi(x)" class="ee_img tr_noresize" eeimg="1"> 满足

<img src="https://www.zhihu.com/equation?tex=\Phi'(x)=A(x)\Phi(x)
  \tag{11}
  " alt="\Phi'(x)=A(x)\Phi(x)
  \tag{11}
  " class="ee_img tr_noresize" eeimg="1">
  代入（10）有

<img src="https://www.zhihu.com/equation?tex=\Phi(x)C'(x)=f(x)
  \tag{12}
  " alt="\Phi(x)C'(x)=f(x)
  \tag{12}
  " class="ee_img tr_noresize" eeimg="1">
  从而

<img src="https://www.zhihu.com/equation?tex=C'(x)=\Phi^{-1}(x)f(x)
  \tag{13}
  " alt="C'(x)=\Phi^{-1}(x)f(x)
  \tag{13}
  " class="ee_img tr_noresize" eeimg="1">
  积分有

<img src="https://www.zhihu.com/equation?tex=C(x)=\int_{x_0}^x\Phi^{-1}(t)f(t)dt+C(x_0)
  \tag{14}
  " alt="C(x)=\int_{x_0}^x\Phi^{-1}(t)f(t)dt+C(x_0)
  \tag{14}
  " class="ee_img tr_noresize" eeimg="1">
  （注意此处是为了避免符合歧义，将被积分的 <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> 写为 <img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1"> ）
  取 <img src="https://www.zhihu.com/equation?tex=C(x_0)=0" alt="C(x_0)=0" class="ee_img tr_noresize" eeimg="1"> ，就可以得到特解

<img src="https://www.zhihu.com/equation?tex=Y(x)=\Phi(x)\int_{x_0}^x\Phi^{-1}(t)f(t)dt
  \tag{15}
  " alt="Y(x)=\Phi(x)\int_{x_0}^x\Phi^{-1}(t)f(t)dt
  \tag{15}
  " class="ee_img tr_noresize" eeimg="1">
  **定理8** 如果 <img src="https://www.zhihu.com/equation?tex=\Phi(x)" alt="\Phi(x)" class="ee_img tr_noresize" eeimg="1"> 是方程组（4）的一个基解矩阵，那么（3）的通解为

<img src="https://www.zhihu.com/equation?tex=y=\Phi(x)(\int_{x_0}^x\Phi^{-1}(t)f(t)dt+C), \quad x\in I
  \tag{16}
  " alt="y=\Phi(x)(\int_{x_0}^x\Phi^{-1}(t)f(t)dt+C), \quad x\in I
  \tag{16}
  " class="ee_img tr_noresize" eeimg="1">
  （*注意上述都是矩阵或者列向量的符号！！！*）

##### 2. <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 阶线性微分方程的通解结构

如果只含有一个未知函数 <img src="https://www.zhihu.com/equation?tex=y=y(x)" alt="y=y(x)" class="ee_img tr_noresize" eeimg="1"> 

<img src="https://www.zhihu.com/equation?tex=y^{(n)}+p_1(x)y^{(n-1)}+\cdots+p_{(n-1)}(x)y'+p_n(x)y=f(x)
\tag{17}
" alt="y^{(n)}+p_1(x)y^{(n-1)}+\cdots+p_{(n-1)}(x)y'+p_n(x)y=f(x)
\tag{17}
" class="ee_img tr_noresize" eeimg="1">
设初值条件

<img src="https://www.zhihu.com/equation?tex=x=x_0,y=y_1^0,y'=y_2^0,\cdots,y^{(n-1)}=y_n^0
\tag{18}
" alt="x=x_0,y=y_1^0,y'=y_2^0,\cdots,y^{(n-1)}=y_n^0
\tag{18}
" class="ee_img tr_noresize" eeimg="1">
根据笔记（二），假设函数 <img src="https://www.zhihu.com/equation?tex=p_1,\cdots,p_n,f" alt="p_1,\cdots,p_n,f" class="ee_img tr_noresize" eeimg="1"> 在区间内都连续，那么解存在且唯一。
同样地，当 <img src="https://www.zhihu.com/equation?tex=f(x)\neq 0" alt="f(x)\neq 0" class="ee_img tr_noresize" eeimg="1"> 时，（17）为 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 阶线性非齐次方程；当 <img src="https://www.zhihu.com/equation?tex=f(x)\equiv 0" alt="f(x)\equiv 0" class="ee_img tr_noresize" eeimg="1"> 时，为 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 阶线性齐次方程。

<img src="https://www.zhihu.com/equation?tex=y^{(n)}+p_1(x)y^{(n-1)}+\cdots+p_{(n-1)}(x)y'+p_n(x)y=0
\tag{19}
" alt="y^{(n)}+p_1(x)y^{(n-1)}+\cdots+p_{(n-1)}(x)y'+p_n(x)y=0
\tag{19}
" class="ee_img tr_noresize" eeimg="1">
为了简便书写，引入**线性微分算子**

<img src="https://www.zhihu.com/equation?tex=L_n=\frac{d^n}{dx^n}+p_1(x)\frac{d^{n-1}}{dx^{n-1}}+\cdots+p_{n-1}(x)\frac{d}{dx}+p_n(x)
\tag{20}
" alt="L_n=\frac{d^n}{dx^n}+p_1(x)\frac{d^{n-1}}{dx^{n-1}}+\cdots+p_{n-1}(x)\frac{d}{dx}+p_n(x)
\tag{20}
" class="ee_img tr_noresize" eeimg="1">
从而微分方程可分别改写为

<img src="https://www.zhihu.com/equation?tex=L_ny=f(x)
\tag{21}
" alt="L_ny=f(x)
\tag{21}
" class="ee_img tr_noresize" eeimg="1">
与

<img src="https://www.zhihu.com/equation?tex=L_ny=0
\tag{22}
" alt="L_ny=0
\tag{22}
" class="ee_img tr_noresize" eeimg="1">
用新的未知数代替 <img src="https://www.zhihu.com/equation?tex=y" alt="y" class="ee_img tr_noresize" eeimg="1"> 的各阶导数，使得书写更加简便

<img src="https://www.zhihu.com/equation?tex=y=y_1,y'=y_2,\cdots,y^{(n-1)}=y_n
\tag{23}
" alt="y=y_1,y'=y_2,\cdots,y^{(n-1)}=y_n
\tag{23}
" class="ee_img tr_noresize" eeimg="1">
进而方程（17）可以简化为方程组

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
y_1'=y_2 \\
y_2'=y_3 \\
\cdots \cdots \\
y_{n-1}'=y_n \\
y_n'=-p_n(x)y_1-\cdots-p_1(x)y_n+f(x)
\end{cases}
\tag{24}
" alt="\begin{cases}
y_1'=y_2 \\
y_2'=y_3 \\
\cdots \cdots \\
y_{n-1}'=y_n \\
y_n'=-p_n(x)y_1-\cdots-p_1(x)y_n+f(x)
\end{cases}
\tag{24}
" class="ee_img tr_noresize" eeimg="1">
改用矩阵表示

<img src="https://www.zhihu.com/equation?tex=\frac{dy}{dx}=A(x)y+F(x)
\tag{25}
" alt="\frac{dy}{dx}=A(x)y+F(x)
\tag{25}
" class="ee_img tr_noresize" eeimg="1">
其中

<img src="https://www.zhihu.com/equation?tex=y=\left(
 \begin{matrix}
   y_1 \\
   y_2 \\
   \vdots \\
   y_n
  \end{matrix}
  \right),
  F(x)=\left(
 \begin{matrix}
   0 \\
   0 \\
   \vdots \\
   f(x)
  \end{matrix}
  \right),\\
  A(x)=\left(
 \begin{matrix}
   0 & 1 & 0 & \cdots & 0 \\
   0 & 0 & 1 & \cdots & 0 \\
   \vdots & \vdots & \vdots & \ddots & \vdots \\
   0 & 0 & 0 & \cdots & 1 \\
   -p_n(x) & -p_{n-1}(x) & -P_{n-2}(x) & \cdots & -p_1(x) \\
  \end{matrix}
  \right),\\
  trA(x)=-p_1(x).
  \tag{26}
" alt="y=\left(
 \begin{matrix}
   y_1 \\
   y_2 \\
   \vdots \\
   y_n
  \end{matrix}
  \right),
  F(x)=\left(
 \begin{matrix}
   0 \\
   0 \\
   \vdots \\
   f(x)
  \end{matrix}
  \right),\\
  A(x)=\left(
 \begin{matrix}
   0 & 1 & 0 & \cdots & 0 \\
   0 & 0 & 1 & \cdots & 0 \\
   \vdots & \vdots & \vdots & \ddots & \vdots \\
   0 & 0 & 0 & \cdots & 1 \\
   -p_n(x) & -p_{n-1}(x) & -P_{n-2}(x) & \cdots & -p_1(x) \\
  \end{matrix}
  \right),\\
  trA(x)=-p_1(x).
  \tag{26}
" class="ee_img tr_noresize" eeimg="1">
相应的，齐次方程可化为

<img src="https://www.zhihu.com/equation?tex=\frac{dy}{dx}=A(x)y
\tag{27}
" alt="\frac{dy}{dx}=A(x)y
\tag{27}
" class="ee_img tr_noresize" eeimg="1">
设 (纯量)（**纯量也就是标量，指只有大小没有方向的量**） 函数组

<img src="https://www.zhihu.com/equation?tex=\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x),
\tag{28}
" alt="\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x),
\tag{28}
" class="ee_img tr_noresize" eeimg="1">

分别是齐次线性微分方程（17）的  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1">  个解, 代入（23），可以得到  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1">  个相应的解为

<img src="https://www.zhihu.com/equation?tex=\left(\begin{array}{c}
\varphi_1(x) \\
\varphi_1^{\prime}(x) \\
\vdots \\
\varphi_1^{(n-1)}(x)
\end{array}\right),\left(\begin{array}{c}
\varphi_2(x) \\
\varphi_2^{\prime}(x) \\
\vdots \\
\varphi_2^{(n-1)}(x)
\end{array}\right), \cdots,\left(\begin{array}{c}
\varphi_n(x) \\
\varphi_n^{\prime}(x) \\
\vdots \\
\varphi_n^{(n-1)}(x)
\end{array}\right) .
\tag{29}
" alt="\left(\begin{array}{c}
\varphi_1(x) \\
\varphi_1^{\prime}(x) \\
\vdots \\
\varphi_1^{(n-1)}(x)
\end{array}\right),\left(\begin{array}{c}
\varphi_2(x) \\
\varphi_2^{\prime}(x) \\
\vdots \\
\varphi_2^{(n-1)}(x)
\end{array}\right), \cdots,\left(\begin{array}{c}
\varphi_n(x) \\
\varphi_n^{\prime}(x) \\
\vdots \\
\varphi_n^{(n-1)}(x)
\end{array}\right) .
\tag{29}
" class="ee_img tr_noresize" eeimg="1">

它们的朗斯基行列式为

<img src="https://www.zhihu.com/equation?tex=W(x)=\left|\begin{array}{cccc}
\varphi_1(x) & \varphi_2(x) & \cdots & \varphi_n(x) \\
\varphi_1^{\prime}(x) & \phi_2^{\prime}(x) & \cdots & \varphi_n^{\prime}(x) \\
\cdots & \cdots & \cdots & \cdots \\
q_1^{(n-1)}(x) & q_2^{(n-1)}(x) & \cdots & \varphi_n^{(n-1)}(x)
\end{array}\right| .
\tag{30}
" alt="W(x)=\left|\begin{array}{cccc}
\varphi_1(x) & \varphi_2(x) & \cdots & \varphi_n(x) \\
\varphi_1^{\prime}(x) & \phi_2^{\prime}(x) & \cdots & \varphi_n^{\prime}(x) \\
\cdots & \cdots & \cdots & \cdots \\
q_1^{(n-1)}(x) & q_2^{(n-1)}(x) & \cdots & \varphi_n^{(n-1)}(x)
\end{array}\right| .
\tag{30}
" class="ee_img tr_noresize" eeimg="1">

不难发现，在（30）这个行列式中, 从第二行开始的各行都是由前一行求导所得。（30）称为 (纯量)函数组（28）的朗斯基行列式。

**定理9**  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个解**线性相关**的充要条件
设函数  <img src="https://www.zhihu.com/equation?tex=\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)," alt="\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)," class="ee_img tr_noresize" eeimg="1"> 是（19）的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个解，则它们在 <img src="https://www.zhihu.com/equation?tex=I" alt="I" class="ee_img tr_noresize" eeimg="1"> 上线性相关的充要条件是

<img src="https://www.zhihu.com/equation?tex=W(x)=W\left[\varphi_1, \cdots, \varphi_n\right]=0, \quad \forall x \in I .
\tag{31}
" alt="W(x)=W\left[\varphi_1, \cdots, \varphi_n\right]=0, \quad \forall x \in I .
\tag{31}
" class="ee_img tr_noresize" eeimg="1">
**定理10** 齐次线性微分方程（19）一定存在 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个线性无关的解。

**定理11** **齐次线性微分方程的通解结构**
设函数  <img src="https://www.zhihu.com/equation?tex=\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)," alt="\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)," class="ee_img tr_noresize" eeimg="1"> 是（19）的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个线性无关的解，则方程（19）任意一个解  <img src="https://www.zhihu.com/equation?tex=y(x)" alt="y(x)" class="ee_img tr_noresize" eeimg="1">  都可表示为  <img src="https://www.zhihu.com/equation?tex=\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)" alt="\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)" class="ee_img tr_noresize" eeimg="1">  的线性组合

<img src="https://www.zhihu.com/equation?tex=y(x)=c_1 \varphi_1(x)+c_2 \varphi_2(x)+\cdots+c_n \varphi_n(x) .
\tag{32}
" alt="y(x)=c_1 \varphi_1(x)+c_2 \varphi_2(x)+\cdots+c_n \varphi_n(x) .
\tag{32}
" class="ee_img tr_noresize" eeimg="1">

也即通解，其中  <img src="https://www.zhihu.com/equation?tex=c_1, c_2, \cdots, c_n" alt="c_1, c_2, \cdots, c_n" class="ee_img tr_noresize" eeimg="1">  为  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个(独立的) 任意常数。

也就是说， <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1">  阶线性齐次方程（19）的线性无关解的最大个数为  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> . 每一个含有  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1">  个线性无关解的解组称为方程（19）的一个基本解组。

**定理12** **刘维尔公式**
设函数  <img src="https://www.zhihu.com/equation?tex=\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)," alt="\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)," class="ee_img tr_noresize" eeimg="1"> 是（19）的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个解， 则它们的朗斯基行列式  <img src="https://www.zhihu.com/equation?tex=W(x)=W [\varphi_1, \varphi_2, \cdots,\left.\varphi_n\right]" alt="W(x)=W [\varphi_1, \varphi_2, \cdots,\left.\varphi_n\right]" class="ee_img tr_noresize" eeimg="1">  满足刘维尔公式

<img src="https://www.zhihu.com/equation?tex=W(x)=W\left(x_0\right) \exp \left(-\int_{x_0}^x p_1(t) \mathrm{d} t\right) .
\tag{33}
" alt="W(x)=W\left(x_0\right) \exp \left(-\int_{x_0}^x p_1(t) \mathrm{d} t\right) .
\tag{33}
" class="ee_img tr_noresize" eeimg="1">

**推论** 方程（19）的解  <img src="https://www.zhihu.com/equation?tex=\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x), x \in I" alt="\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x), x \in I" class="ee_img tr_noresize" eeimg="1"> , 的朗斯基行列式  <img src="https://www.zhihu.com/equation?tex=W(x)" alt="W(x)" class="ee_img tr_noresize" eeimg="1">  在区间  <img src="https://www.zhihu.com/equation?tex=I" alt="I" class="ee_img tr_noresize" eeimg="1">  上或者恒为0, 或者恒不为0。这  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个解是基本解组的充要条件是  <img src="https://www.zhihu.com/equation?tex=W(x) \neq 0, \forall x \in I" alt="W(x) \neq 0, \forall x \in I" class="ee_img tr_noresize" eeimg="1"> 。

**定理13** **非齐次线性微分方程的通解结构**
设  <img src="https://www.zhihu.com/equation?tex=\varphi_1(x), \varphi_2(x)" alt="\varphi_1(x), \varphi_2(x)" class="ee_img tr_noresize" eeimg="1"> ,  <img src="https://www.zhihu.com/equation?tex=\cdots, \varphi_n(x)" alt="\cdots, \varphi_n(x)" class="ee_img tr_noresize" eeimg="1">  是方程（19）的一个基本解组, 而  <img src="https://www.zhihu.com/equation?tex=Y(x)" alt="Y(x)" class="ee_img tr_noresize" eeimg="1">  是方程（17）的一个特解, 则方程 (3.19) 的通解为

<img src="https://www.zhihu.com/equation?tex=y=c_1 p_1(x)+c_2 p_2(x)+\cdots+c_n p_n(x)+Y(x),
\tag{34}
" alt="y=c_1 p_1(x)+c_2 p_2(x)+\cdots+c_n p_n(x)+Y(x),
\tag{34}
" class="ee_img tr_noresize" eeimg="1">

其中  <img src="https://www.zhihu.com/equation?tex=c_1, c_2, \cdots, c_n" alt="c_1, c_2, \cdots, c_n" class="ee_img tr_noresize" eeimg="1">  为  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1">  个(独立的) 任意常数.

**定理14** 若已知  <img src="https://www.zhihu.com/equation?tex=\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)" alt="\varphi_1(x), \varphi_2(x), \cdots, \varphi_n(x)" class="ee_img tr_noresize" eeimg="1">  是方程（19）的一个基本解组, 则可通过**常数变易法**（原理同前一小节）求得方程（17）的特解  <img src="https://www.zhihu.com/equation?tex=Y(x)" alt="Y(x)" class="ee_img tr_noresize" eeimg="1">  ，其计算公式为

<img src="https://www.zhihu.com/equation?tex=Y(x)=\sum_{i=1}^n \varphi_i(x) \int_{x_0}^x \frac{W_{n i}(t)}{W(t)} f(t) \mathrm{d} t,
\tag{35}
" alt="Y(x)=\sum_{i=1}^n \varphi_i(x) \int_{x_0}^x \frac{W_{n i}(t)}{W(t)} f(t) \mathrm{d} t,
\tag{35}
" class="ee_img tr_noresize" eeimg="1">

其中  <img src="https://www.zhihu.com/equation?tex=W_{n i}(t)" alt="W_{n i}(t)" class="ee_img tr_noresize" eeimg="1">  是朗斯基行列式  <img src="https://www.zhihu.com/equation?tex=W(t)" alt="W(t)" class="ee_img tr_noresize" eeimg="1">  中第  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1">  行第  <img src="https://www.zhihu.com/equation?tex=i" alt="i" class="ee_img tr_noresize" eeimg="1">  列元素的代数余子式，即用  <img src="https://www.zhihu.com/equation?tex=(0, \cdots, 0,1)^T" alt="(0, \cdots, 0,1)^T" class="ee_img tr_noresize" eeimg="1">  替换  <img src="https://www.zhihu.com/equation?tex=W(t)" alt="W(t)" class="ee_img tr_noresize" eeimg="1">  的第  <img src="https://www.zhihu.com/equation?tex=i" alt="i" class="ee_img tr_noresize" eeimg="1">  列后所得到的行列式。

![87845f5a3c67d169502dcd2968ebdff](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（三）/87845f5a3c67d169502dcd2968ebdff.png)

**定理15** 设实变量  <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">  的复值函数  <img src="https://www.zhihu.com/equation?tex=y=y_1(x)+\mathrm{i} y_2(x)" alt="y=y_1(x)+\mathrm{i} y_2(x)" class="ee_img tr_noresize" eeimg="1">  是方程

<img src="https://www.zhihu.com/equation?tex=L_n y=f_1(x)+\mathrm{i} f_2(x)
\tag{36}
" alt="L_n y=f_1(x)+\mathrm{i} f_2(x)
\tag{36}
" class="ee_img tr_noresize" eeimg="1">

的解, 其中  <img src="https://www.zhihu.com/equation?tex=y_1(x), y_2(x), f_1(x), f_2(x)" alt="y_1(x), y_2(x), f_1(x), f_2(x)" class="ee_img tr_noresize" eeimg="1">  都是实值函数,则  <img src="https://www.zhihu.com/equation?tex=y_1(x)" alt="y_1(x)" class="ee_img tr_noresize" eeimg="1">  与  <img src="https://www.zhihu.com/equation?tex=y_2(x)" alt="y_2(x)" class="ee_img tr_noresize" eeimg="1">  分别是方程

<img src="https://www.zhihu.com/equation?tex=L_n y=f_1(x) \text { 与 } L_n y=f_2(x)
\tag{37}
" alt="L_n y=f_1(x) \text { 与 } L_n y=f_2(x)
\tag{37}
" class="ee_img tr_noresize" eeimg="1">

的解。特别, 若  <img src="https://www.zhihu.com/equation?tex=y=y_1(x)+\mathrm{i} y_2(x)" alt="y=y_1(x)+\mathrm{i} y_2(x)" class="ee_img tr_noresize" eeimg="1">  是齐次方程

<img src="https://www.zhihu.com/equation?tex=L_n y=0
\tag{38}
" alt="L_n y=0
\tag{38}
" class="ee_img tr_noresize" eeimg="1">

的解。則  <img src="https://www.zhihu.com/equation?tex=y_1(x)" alt="y_1(x)" class="ee_img tr_noresize" eeimg="1">  和  <img src="https://www.zhihu.com/equation?tex=y_2(x)" alt="y_2(x)" class="ee_img tr_noresize" eeimg="1">  都是方程  <img src="https://www.zhihu.com/equation?tex=L_n y=0" alt="L_n y=0" class="ee_img tr_noresize" eeimg="1">  的解。

###  <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 6 高阶线性微分方程的降阶法

除了把 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 阶线性齐次方程的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个线性无关解全部解出，从而求其通解以外，我们还可以求出方程的一个特解 <img src="https://www.zhihu.com/equation?tex=y_1(x)" alt="y_1(x)" class="ee_img tr_noresize" eeimg="1"> ，进而作变换 <img src="https://www.zhihu.com/equation?tex=y=y_1(x)z" alt="y=y_1(x)z" class="ee_img tr_noresize" eeimg="1"> ，于是可以把阶数降为 <img src="https://www.zhihu.com/equation?tex=n-1" alt="n-1" class="ee_img tr_noresize" eeimg="1"> 。

我们以二阶线性齐次方程为讨论对象。

##### 1. 二阶线性齐次方程的降阶法

对于方程

<img src="https://www.zhihu.com/equation?tex=y''+p(x)y'+q(x)y=0
\tag{39}
" alt="y''+p(x)y'+q(x)y=0
\tag{39}
" class="ee_img tr_noresize" eeimg="1">
设它的一个特解为 <img src="https://www.zhihu.com/equation?tex=y=y_1(x)" alt="y=y_1(x)" class="ee_img tr_noresize" eeimg="1"> ，作未知函数的变换

<img src="https://www.zhihu.com/equation?tex=y=y_1(x)z
\tag{40}
" alt="y=y_1(x)z
\tag{40}
" class="ee_img tr_noresize" eeimg="1">
将（40）代入方程（39），可以得到

<img src="https://www.zhihu.com/equation?tex=y_1z''+(2y_1'z'+p(x)y_1)z'+(y_1''+p(x)y_1'+q(x)y_1)z=0
\tag{41}
" alt="y_1z''+(2y_1'z'+p(x)y_1)z'+(y_1''+p(x)y_1'+q(x)y_1)z=0
\tag{41}
" class="ee_img tr_noresize" eeimg="1">
而（41）的最后一项等于0，再利用变量代换 <img src="https://www.zhihu.com/equation?tex=z'=u" alt="z'=u" class="ee_img tr_noresize" eeimg="1"> ，从而得到

<img src="https://www.zhihu.com/equation?tex=y_1u'+(2y_1'+p(x)y_1)u=0
\tag{42}
" alt="y_1u'+(2y_1'+p(x)y_1)u=0
\tag{42}
" class="ee_img tr_noresize" eeimg="1">
这已经是我们之前解决过的一阶微分方程了，注意这里的 <img src="https://www.zhihu.com/equation?tex=z" alt="z" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1"> 都是 <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> 的函数。积分得

<img src="https://www.zhihu.com/equation?tex=z'=u=\frac{C_1}{y_1^2}e^{-\int p(x)dx}
\tag{43}
" alt="z'=u=\frac{C_1}{y_1^2}e^{-\int p(x)dx}
\tag{43}
" class="ee_img tr_noresize" eeimg="1">
再积分得

<img src="https://www.zhihu.com/equation?tex=z=C_1\int \frac{1}{y^2_1}e^{-\int p(x)dx}dx+C_2
\tag{44}
" alt="z=C_1\int \frac{1}{y^2_1}e^{-\int p(x)dx}dx+C_2
\tag{44}
" class="ee_img tr_noresize" eeimg="1">
从而得到通解

<img src="https://www.zhihu.com/equation?tex=y=y_1z=C_1y_1\int \frac{1}{y^2_1}e^{-\int p(x)dx}dx+C_2y_1
\tag{45}
" alt="y=y_1z=C_1y_1\int \frac{1}{y^2_1}e^{-\int p(x)dx}dx+C_2y_1
\tag{45}
" class="ee_img tr_noresize" eeimg="1">
再根据第5节的内容，可以得到另一个线性无关的特解为

<img src="https://www.zhihu.com/equation?tex=y_1\int \frac{1}{y^2_1}e^{-\int p(x)dx}dx
\tag{46}
" alt="y_1\int \frac{1}{y^2_1}e^{-\int p(x)dx}dx
\tag{46}
" class="ee_img tr_noresize" eeimg="1">
对于非齐次方程，我们把它对应的齐次方程的一个特解找到，再按上述方法操作即可。

##### 2.刘维尔公式

特解 <img src="https://www.zhihu.com/equation?tex=y_1(x)" alt="y_1(x)" class="ee_img tr_noresize" eeimg="1"> 与解 <img src="https://www.zhihu.com/equation?tex=y(x)" alt="y(x)" class="ee_img tr_noresize" eeimg="1"> 满足刘维尔公式

<img src="https://www.zhihu.com/equation?tex=\begin{vmatrix}
y_1 & y \\
y_1' & y' \\
\end{vmatrix}
=Ce^{-\int p(x)dx}
\tag{47}
" alt="\begin{vmatrix}
y_1 & y \\
y_1' & y' \\
\end{vmatrix}
=Ce^{-\int p(x)dx}
\tag{47}
" class="ee_img tr_noresize" eeimg="1">
从而得到一阶线性方程

<img src="https://www.zhihu.com/equation?tex=y'-\frac{y_1'}{y_1}y=\frac{C}{y_1}e^{-\int p(x)dx}
\tag{48}
" alt="y'-\frac{y_1'}{y_1}y=\frac{C}{y_1}e^{-\int p(x)dx}
\tag{48}
" class="ee_img tr_noresize" eeimg="1">
最终得到与（45）相同的结果。

###  <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 7  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 阶常系数线性方程

##### 1.  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 阶常系数线性齐次方程


<img src="https://www.zhihu.com/equation?tex=L_ny=y^{(n)}+p_1y^{(n-1)}+\cdots+p_{(n-1)}y'+p_ny=0
\tag{49}
" alt="L_ny=y^{(n)}+p_1y^{(n-1)}+\cdots+p_{(n-1)}y'+p_ny=0
\tag{49}
" class="ee_img tr_noresize" eeimg="1">

设特解形式为 <img src="https://www.zhihu.com/equation?tex=e^{\lambda x}" alt="e^{\lambda x}" class="ee_img tr_noresize" eeimg="1"> ，代入方程（49），得到待定常数 <img src="https://www.zhihu.com/equation?tex=\lambda" alt="\lambda" class="ee_img tr_noresize" eeimg="1"> 满足的 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 次代数方程

<img src="https://www.zhihu.com/equation?tex=\varphi(\lambda)=\lambda^n+p_1\lambda^{n-1}+\cdots+p_{n-1}\lambda+p_n=0
\tag{50}
" alt="\varphi(\lambda)=\lambda^n+p_1\lambda^{n-1}+\cdots+p_{n-1}\lambda+p_n=0
\tag{50}
" class="ee_img tr_noresize" eeimg="1">
称为**特征方程**，其 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个根称为**特征根**。

**定理** 设特征方程（50）的不同根为 <img src="https://www.zhihu.com/equation?tex=\lambda_1,\cdots,\lambda_s" alt="\lambda_1,\cdots,\lambda_s" class="ee_img tr_noresize" eeimg="1"> ，且 <img src="https://www.zhihu.com/equation?tex=\lambda_i" alt="\lambda_i" class="ee_img tr_noresize" eeimg="1"> 是 <img src="https://www.zhihu.com/equation?tex=m_i" alt="m_i" class="ee_img tr_noresize" eeimg="1"> 重根， <img src="https://www.zhihu.com/equation?tex=i=1,\cdots,s,\sum_{i=1}^sm_i=n" alt="i=1,\cdots,s,\sum_{i=1}^sm_i=n" class="ee_img tr_noresize" eeimg="1"> ，那么方程（49）的基本解组是

<img src="https://www.zhihu.com/equation?tex=x^ke^{\lambda_ix},k=0,1,\cdots,m_1-1;i=1,\cdots,s.
\tag{51}
" alt="x^ke^{\lambda_ix},k=0,1,\cdots,m_1-1;i=1,\cdots,s.
\tag{51}
" class="ee_img tr_noresize" eeimg="1">
证明过程直接截取教材：
![f4c5bd617a21176f13899ba676322ba](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（三）/f4c5bd617a21176f13899ba676322ba.png)

![93ebf27ae36dec1f3e5ed08db38dd1a](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（三）/93ebf27ae36dec1f3e5ed08db38dd1a.png)

而对于特征根是复数根 <img src="https://www.zhihu.com/equation?tex=\alpha \pm i\beta" alt="\alpha \pm i\beta" class="ee_img tr_noresize" eeimg="1"> 的情况，可以用两个实值代替复数解

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
e^{\alpha x}\cos \beta x = (e^{(\alpha+i\beta)x}+e^{(\alpha-i\beta)x})/2 \\
e^{\alpha x}\sin \beta x = (e^{(\alpha+i\beta)x}-e^{(\alpha-i\beta)x})/2i
\end{cases}
\tag{52}
" alt="\begin{cases}
e^{\alpha x}\cos \beta x = (e^{(\alpha+i\beta)x}+e^{(\alpha-i\beta)x})/2 \\
e^{\alpha x}\sin \beta x = (e^{(\alpha+i\beta)x}-e^{(\alpha-i\beta)x})/2i
\end{cases}
\tag{52}
" class="ee_img tr_noresize" eeimg="1">
从而得到以下的结论：
![ce8da1f1b57fd77c8ad4d4fedd11713](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（三）/ce8da1f1b57fd77c8ad4d4fedd11713.png)

##### 2.  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 阶常系数线性非齐次方程


<img src="https://www.zhihu.com/equation?tex=L_ny=y^{(n)}+p_1y^{(n-1)}+\cdots+p_{(n-1)}y'+p_ny=f(x)
\tag{53}
" alt="L_ny=y^{(n)}+p_1y^{(n-1)}+\cdots+p_{(n-1)}y'+p_ny=f(x)
\tag{53}
" class="ee_img tr_noresize" eeimg="1">

根据之前讨论过的解的结构，我们已经得到了非齐次方程对应齐次方程的通解，现在只需要找到方程的一个特解即可。

与解二阶常系数线性非齐次方程同理，可以采用待定系数法。由于懒惰的原因，就直接截取教材图片吧~

![b92f883f6e6c278c559fa5b75480d88](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（三）/b92f883f6e6c278c559fa5b75480d88.png)

![07fdc4cb398c53dc9963248cc877b60](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（三）/07fdc4cb398c53dc9963248cc877b60.png)

*掌握上面的方法还是需要例题作为练习！！！（对个人而言）*

###  <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 8 可化为常系数线性方程的线性微分方程

##### 1. 欧拉方程


<img src="https://www.zhihu.com/equation?tex=x^ny^{(n)}+p_1x^{n-1}y^{(n-1)}+\cdots+p_{n-1}xy'+p_ny=f(x)
\tag{53}
" alt="x^ny^{(n)}+p_1x^{n-1}y^{(n-1)}+\cdots+p_{n-1}xy'+p_ny=f(x)
\tag{53}
" class="ee_img tr_noresize" eeimg="1">

可做变换（同之前解决二阶方程一样的道理） <img src="https://www.zhihu.com/equation?tex=x=e^t" alt="x=e^t" class="ee_img tr_noresize" eeimg="1"> 或 <img src="https://www.zhihu.com/equation?tex=x=e^{-t}" alt="x=e^{-t}" class="ee_img tr_noresize" eeimg="1"> （总之要使 <img src="https://www.zhihu.com/equation?tex=e^t>0" alt="e^t>0" class="ee_img tr_noresize" eeimg="1"> ）。再引入符号简化书写 <img src="https://www.zhihu.com/equation?tex=D=\frac{d}{dt},D^k=\frac{d^k}{dt^k}" alt="D=\frac{d}{dt},D^k=\frac{d^k}{dt^k}" class="ee_img tr_noresize" eeimg="1"> ，那么用数学归纳法可证得（证明过程较简单）：

<img src="https://www.zhihu.com/equation?tex=\frac{d^ky}{dx^k}=\frac{1}{x^k}D(D-1)\cdots(D-k+1)y
\tag{54}
" alt="\frac{d^ky}{dx^k}=\frac{1}{x^k}D(D-1)\cdots(D-k+1)y
\tag{54}
" class="ee_img tr_noresize" eeimg="1">
从而（53）的左侧的一般项可以化为

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
p_{n-k}x^ky^{(k)} &= p_{n-k}D(D-1)\cdots(D-k+1)y \\
&=p_{n-k}(\frac{d^ky}{dt^k}+a_1\frac{d^{k-1}y}{dt^{k-1}}+\cdots+a_{k-1}\frac{dy}{dt})
\end{aligned}
\tag{55}
" alt="\begin{aligned}
p_{n-k}x^ky^{(k)} &= p_{n-k}D(D-1)\cdots(D-k+1)y \\
&=p_{n-k}(\frac{d^ky}{dt^k}+a_1\frac{d^{k-1}y}{dt^{k-1}}+\cdots+a_{k-1}\frac{dy}{dt})
\end{aligned}
\tag{55}
" class="ee_img tr_noresize" eeimg="1">

##### 2.用未知函数的线性变换消去二阶线性方程中的一阶导数项

对于

<img src="https://www.zhihu.com/equation?tex=y''+p(x)y'+q(x)y=f(x)
\tag{56}
" alt="y''+p(x)y'+q(x)y=f(x)
\tag{56}
" class="ee_img tr_noresize" eeimg="1">
可做作变换 <img src="https://www.zhihu.com/equation?tex=y=u(x)z" alt="y=u(x)z" class="ee_img tr_noresize" eeimg="1"> 。（当 <img src="https://www.zhihu.com/equation?tex=u(x)" alt="u(x)" class="ee_img tr_noresize" eeimg="1"> 为方程（56）相应齐次方程的一个特解时，其实就是前面所学的降阶法。）

<img src="https://www.zhihu.com/equation?tex=uz''+(2u'+p(x)u)z'+(u''+p(x)u'+q(x)u)z=f(x)
\tag{57}
" alt="uz''+(2u'+p(x)u)z'+(u''+p(x)u'+q(x)u)z=f(x)
\tag{57}
" class="ee_img tr_noresize" eeimg="1">
令 <img src="https://www.zhihu.com/equation?tex=z'" alt="z'" class="ee_img tr_noresize" eeimg="1"> 的系数为0

<img src="https://www.zhihu.com/equation?tex=2u'+p(x)u=0
\tag{58}
" alt="2u'+p(x)u=0
\tag{58}
" class="ee_img tr_noresize" eeimg="1">
这是一个 <img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1"> 的一阶微分方程

<img src="https://www.zhihu.com/equation?tex=u=\exp(-\frac{1}{2}\int p(x)dx)
\tag{59}
" alt="u=\exp(-\frac{1}{2}\int p(x)dx)
\tag{59}
" class="ee_img tr_noresize" eeimg="1">
再令

<img src="https://www.zhihu.com/equation?tex=I(x)\equiv q(x)-\frac{1}{4}p^2(x)-\frac{1}{2}p'(x)
\tag{60}
" alt="I(x)\equiv q(x)-\frac{1}{4}p^2(x)-\frac{1}{2}p'(x)
\tag{60}
" class="ee_img tr_noresize" eeimg="1">
从而方程（57）可以变为

<img src="https://www.zhihu.com/equation?tex=z''+I(x)z=f(x)e^{(-\frac{1}{2}\int p(x)dx)}
\tag{61}
" alt="z''+I(x)z=f(x)e^{(-\frac{1}{2}\int p(x)dx)}
\tag{61}
" class="ee_img tr_noresize" eeimg="1">
（1）当 <img src="https://www.zhihu.com/equation?tex=I(x)=C" alt="I(x)=C" class="ee_img tr_noresize" eeimg="1"> 时，（61）化为常系数方程，容易求得通解。

（2）当 <img src="https://www.zhihu.com/equation?tex=I(x)=\frac{C}{x^2}" alt="I(x)=\frac{C}{x^2}" class="ee_img tr_noresize" eeimg="1"> 时，化为欧拉方程。

（3）当 <img src="https://www.zhihu.com/equation?tex=I(x)=-\frac{\varphi''(x)}{\varphi(x)}" alt="I(x)=-\frac{\varphi''(x)}{\varphi(x)}" class="ee_img tr_noresize" eeimg="1"> 时，显然 <img src="https://www.zhihu.com/equation?tex=z=\varphi(x)" alt="z=\varphi(x)" class="ee_img tr_noresize" eeimg="1"> 是一个特解，那么可以用降阶法处理。