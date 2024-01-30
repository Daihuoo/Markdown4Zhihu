# 常微分方程笔记（四）

基于《大学数学教程》（第二册）的常微分方程学习笔记，这篇内容包含了最后几个小节的内容。由于本人水平有限，大部分都是直接来源于书本内容，可能会有公式拼写等错误。最后两个小节的内容仅仅把书中的定义，定理以及推论列出。

###  <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 9 一阶常系数线性微分方程组

利用**消元法**，将一阶常系数线性微分方程组化为高阶常系数线性方程。

与解方程组的基本思想相同，**即用其中一个未知函数以及这个未知函数的各阶导数，来表示其他未知函数。再代入其他函数所满足的关系式后，可以得到这一未知函数所满足的高阶常系数线性方程。**充分**利用求导来进行消元**。

**注：**可能会出现多于的任意常数，因此计算出答案之后，还需进行检验的操作。

而对于含两个未知数的常系数线性微分方程组

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
P_{11}(D)x+P_{12}(D)y = F_1(t) \\
P_{21}(D)x+P_{22}(D)y = F_2(t) 
\end{cases}
\tag{1}
" alt="\begin{cases}
P_{11}(D)x+P_{12}(D)y = F_1(t) \\
P_{21}(D)x+P_{22}(D)y = F_2(t) 
\end{cases}
\tag{1}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=D=\frac{d}{dt}" alt="D=\frac{d}{dt}" class="ee_img tr_noresize" eeimg="1"> 。那么这个方程组通解所含的独立任意常数的个数等于算子多项式

<img src="https://www.zhihu.com/equation?tex=\Delta(D)=
\begin{vmatrix}
P_{11}(D) & P_{12}(D) \\
P_{21}(D) & P_{22}(D)
\end{vmatrix}
\tag{2}
" alt="\Delta(D)=
\begin{vmatrix}
P_{11}(D) & P_{12}(D) \\
P_{21}(D) & P_{22}(D)
\end{vmatrix}
\tag{2}
" class="ee_img tr_noresize" eeimg="1">
的次数。

###  <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 10 幂级数解法

众所周知，大部分的微分方程都不能用初等函数表示。在解决微分方程的1问题时，我们经常还会用到**幂级数解法**和**数值解法**。下面我们讨论幂级数解法。

##### 1. 一阶方程


<img src="https://www.zhihu.com/equation?tex=y'=f(x,y)
\tag{3}
" alt="y'=f(x,y)
\tag{3}
" class="ee_img tr_noresize" eeimg="1">

如果 <img src="https://www.zhihu.com/equation?tex=f(x,y)" alt="f(x,y)" class="ee_img tr_noresize" eeimg="1"> 在点 <img src="https://www.zhihu.com/equation?tex=(x_0,y_0)" alt="(x_0,y_0)" class="ee_img tr_noresize" eeimg="1"> 的某邻域内可以展开为收敛的泰勒级数

<img src="https://www.zhihu.com/equation?tex=f(x,y)=f(x_0+y_0)+\sum_{k-1}^{\infty}\frac{1}{k!}[(x-x_0)\frac{\partial}{\partial x}+(y-y_0)\frac{\partial}{\partial y}]^kf|_{(x_0,y_0)}
\tag{4}
" alt="f(x,y)=f(x_0+y_0)+\sum_{k-1}^{\infty}\frac{1}{k!}[(x-x_0)\frac{\partial}{\partial x}+(y-y_0)\frac{\partial}{\partial y}]^kf|_{(x_0,y_0)}
\tag{4}
" class="ee_img tr_noresize" eeimg="1">
那么方程（3）存在唯一的满足初值条件 <img src="https://www.zhihu.com/equation?tex=y(x_0)=y_0" alt="y(x_0)=y_0" class="ee_img tr_noresize" eeimg="1"> 的幂级数解

<img src="https://www.zhihu.com/equation?tex=y=y_0+c_1(x-x_0)+c_2(x-x_0)^2+\cdots
\tag{5}
" alt="y=y_0+c_1(x-x_0)+c_2(x-x_0)^2+\cdots
\tag{5}
" class="ee_img tr_noresize" eeimg="1">

##### 2. 二阶方程


<img src="https://www.zhihu.com/equation?tex=y''+p(x)y'+q(x)y=0
\tag{6}
" alt="y''+p(x)y'+q(x)y=0
\tag{6}
" class="ee_img tr_noresize" eeimg="1">

**定义1** 如果 <img src="https://www.zhihu.com/equation?tex=x=x_0" alt="x=x_0" class="ee_img tr_noresize" eeimg="1"> 处函数 <img src="https://www.zhihu.com/equation?tex=p,q" alt="p,q" class="ee_img tr_noresize" eeimg="1"> 都是解析的，也就是说函数可以在 <img src="https://www.zhihu.com/equation?tex=x_0" alt="x_0" class="ee_img tr_noresize" eeimg="1"> 的某邻域内可展开为收敛的泰勒级数，那么就称 <img src="https://www.zhihu.com/equation?tex=x_0" alt="x_0" class="ee_img tr_noresize" eeimg="1"> 点是方程（6）的**常点**；反之，称为**奇点**。

* 对于常点的情况

  **定理1** 设 <img src="https://www.zhihu.com/equation?tex=p,q" alt="p,q" class="ee_img tr_noresize" eeimg="1"> 展开的收敛泰勒级数的公共收敛区间为 <img src="https://www.zhihu.com/equation?tex=(x_0-R,x_0+R)(R>0)" alt="(x_0-R,x_0+R)(R>0)" class="ee_img tr_noresize" eeimg="1"> ，那么在该区间上存在唯一的幂级数解

<img src="https://www.zhihu.com/equation?tex=y=y_0+y_1(x-x_0)+y_2(x-x_0)^2+\cdots
  \tag{7}
  " alt="y=y_0+y_1(x-x_0)+y_2(x-x_0)^2+\cdots
  \tag{7}
  " class="ee_img tr_noresize" eeimg="1">
  且满足初值条件 <img src="https://www.zhihu.com/equation?tex=y(x_0)=y_0,y'(x_0)=y_1" alt="y(x_0)=y_0,y'(x_0)=y_1" class="ee_img tr_noresize" eeimg="1"> 。

  **勒让德方程（Legendre）**

  求方程

<img src="https://www.zhihu.com/equation?tex=(1-x^2)y''-2xy'+m(m+1)y=0
  \tag{8}
  " alt="(1-x^2)y''-2xy'+m(m+1)y=0
  \tag{8}
  " class="ee_img tr_noresize" eeimg="1">
  在 <img src="https://www.zhihu.com/equation?tex=x=0" alt="x=0" class="ee_img tr_noresize" eeimg="1"> 附近的幂级数解。
  ![2ad95f96d4078b08760350bf0fb1660](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/2ad95f96d4078b08760350bf0fb1660.png)

  ![19ba9ec5ccfb1bb225aaa3df8e70f80](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/19ba9ec5ccfb1bb225aaa3df8e70f80.png)

  ![8cf9351464e15aa7617452e9c66dd15](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/8cf9351464e15aa7617452e9c66dd15.png)

* 正则奇点情况

  **定义2** 如果 <img src="https://www.zhihu.com/equation?tex=x=x_0" alt="x=x_0" class="ee_img tr_noresize" eeimg="1"> 已经是奇点了，但 <img src="https://www.zhihu.com/equation?tex=(x-x_0)p(x),(x-x_0)^2q(x)" alt="(x-x_0)p(x),(x-x_0)^2q(x)" class="ee_img tr_noresize" eeimg="1"> 在点 <img src="https://www.zhihu.com/equation?tex=x=x_0" alt="x=x_0" class="ee_img tr_noresize" eeimg="1"> 是解析的，那么 <img src="https://www.zhihu.com/equation?tex=x_0" alt="x_0" class="ee_img tr_noresize" eeimg="1"> 是方程的**正则奇点**，否则是**非正则奇点**。

  **定理2** 广义幂级数解法
  设 <img src="https://www.zhihu.com/equation?tex=(x-x_0)p,(x-x_0)q" alt="(x-x_0)p,(x-x_0)q" class="ee_img tr_noresize" eeimg="1"> 展开的收敛泰勒级数的公共收敛区间为 <img src="https://www.zhihu.com/equation?tex=(x_0-R,x_0+R)(R>0)" alt="(x_0-R,x_0+R)(R>0)" class="ee_img tr_noresize" eeimg="1"> ，那么在 <img src="https://www.zhihu.com/equation?tex=(x_0,x_0+R)" alt="(x_0,x_0+R)" class="ee_img tr_noresize" eeimg="1"> 上有形如

<img src="https://www.zhihu.com/equation?tex=y=(x-x_0)^r\sum_{n=0}^{\infty}a_n(x-x_0)^n,\quad (a_0\neq 0)
  \tag{9}
  " alt="y=(x-x_0)^r\sum_{n=0}^{\infty}a_n(x-x_0)^n,\quad (a_0\neq 0)
  \tag{9}
  " class="ee_img tr_noresize" eeimg="1">
  的广义幂级数解。 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 称为**指标**，可以为正为负，可以是无理数；当 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 是正整数的时候，（9）就退化为幂级数。

  再将（9）代入方程（6），比较幂系数相同的项，可以得到指标以及系数。指标方程为

<img src="https://www.zhihu.com/equation?tex=r(r-1)+p_0r+q_0=0
  \tag{10}
  " alt="r(r-1)+p_0r+q_0=0
  \tag{10}
  " class="ee_img tr_noresize" eeimg="1">
  其中

<img src="https://www.zhihu.com/equation?tex=p_0=\lim_{x \rightarrow x_0}(x-x_0)p(x) \\
  q_0=\lim_{x \rightarrow x_0}(x-x_0)q(x)
  \tag{11}
  " alt="p_0=\lim_{x \rightarrow x_0}(x-x_0)p(x) \\
  q_0=\lim_{x \rightarrow x_0}(x-x_0)q(x)
  \tag{11}
  " class="ee_img tr_noresize" eeimg="1">

### * <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 11 二阶线性方程的若干定性性质

![3aaabc6bf6136a90392178e4ca5abbb](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/3aaabc6bf6136a90392178e4ca5abbb.png)

![image-20240129170344446](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170344446.png)

![image-20240129170427581](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170427581.png)

![image-20240129170448959](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170448959.png)

### * <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 12 一阶微分方程组——首次积分法

![image-20240129170641475](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170641475.png)

![image-20240129170658445](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170658445.png)

![image-20240129170711525](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170711525.png)

![image-20240129170724414](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170724414.png)

![image-20240129170739263](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170739263.png)

![image-20240129170751769](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170751769.png)

![image-20240129170809770](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170809770.png)

![image-20240129170818541](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（四）/image-20240129170818541.png)