# 常微分方程笔记（二）

本篇笔记基于《大学数学教程》（第二册），书接上回的“常微分方程笔记（一）。

###  <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 3 存在唯一性定理

能用初等函数表示的微分方程的解的函数少之又少，一般要求助于近似解法。而在求解近似解之前，必须研究方程解的存在性和唯一性。

##### 1. 已解出导数的一阶微分方程的存在唯一性

对于初值问题

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
y'=f(x,y) \\
y(x_0)=y_0
\end{cases}
\tag{1}
" alt="\begin{cases}
y'=f(x,y) \\
y(x_0)=y_0
\end{cases}
\tag{1}
" class="ee_img tr_noresize" eeimg="1">
**定理1**（皮卡存在唯一性定理）
假设函数 <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> 以及 <img src="https://www.zhihu.com/equation?tex=\frac{\partial f}{\partial y}" alt="\frac{\partial f}{\partial y}" class="ee_img tr_noresize" eeimg="1"> 在闭合矩形区域 <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> 内上连续。其中 <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> 满足 <img src="https://www.zhihu.com/equation?tex=R={(x,y)||x-x_0| \leqslant a,|y-y_0| \leqslant b}" alt="R={(x,y)||x-x_0| \leqslant a,|y-y_0| \leqslant b}" class="ee_img tr_noresize" eeimg="1"> ，那么方程（1）在 <img src="https://www.zhihu.com/equation?tex=|x-x_0|\leqslant h" alt="|x-x_0|\leqslant h" class="ee_img tr_noresize" eeimg="1"> 上存在唯一解 <img src="https://www.zhihu.com/equation?tex=y=\phi(x)" alt="y=\phi(x)" class="ee_img tr_noresize" eeimg="1"> 满足初值条件 <img src="https://www.zhihu.com/equation?tex=\phi(x_0)=y_0" alt="\phi(x_0)=y_0" class="ee_img tr_noresize" eeimg="1"> ，其中

<img src="https://www.zhihu.com/equation?tex=h=min(a,\frac{b}{M}),M=max|f(x,y)|

\tag{2}
" alt="h=min(a,\frac{b}{M}),M=max|f(x,y)|

\tag{2}
" class="ee_img tr_noresize" eeimg="1">
下面证明定理1成立。（由于篇幅较长，直接截取教材中的证明）

1. 首先**构造连续函数序列 <img src="https://www.zhihu.com/equation?tex={y_n(x)}" alt="{y_n(x)}" class="ee_img tr_noresize" eeimg="1"> **（皮卡逐步逼近序列），并证明 <img src="https://www.zhihu.com/equation?tex={y_n(x)}" alt="{y_n(x)}" class="ee_img tr_noresize" eeimg="1"> 在 <img src="https://www.zhihu.com/equation?tex=|x-x_0|\leqslant h" alt="|x-x_0|\leqslant h" class="ee_img tr_noresize" eeimg="1"> 上连续。
   ![4604be3afc4a2143f7782e463958ed1](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（二）/4604be3afc4a2143f7782e463958ed1.png)

![e5eb65ec18283b5fb68a8686371a9e6](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（二）/e5eb65ec18283b5fb68a8686371a9e6.png)

2. 证明该序列在 <img src="https://www.zhihu.com/equation?tex=|x-x_0|\leqslant h" alt="|x-x_0|\leqslant h" class="ee_img tr_noresize" eeimg="1"> 上**一致收敛且绝对收敛于 <img src="https://www.zhihu.com/equation?tex=\phi(x)" alt="\phi(x)" class="ee_img tr_noresize" eeimg="1"> **。
   ![bf1111bbd595d626481cc1cd6e8c621](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（二）/bf1111bbd595d626481cc1cd6e8c621.png)

![71a8c46917209fe977b37e91f7d0faf](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（二）/71a8c46917209fe977b37e91f7d0faf.png)

3. 证明收敛的函数 <img src="https://www.zhihu.com/equation?tex=\phi(x)" alt="\phi(x)" class="ee_img tr_noresize" eeimg="1"> **满足微分方程**（1）。
   ![c6c5f07565bd9646becd0d475f8006a](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（二）/c6c5f07565bd9646becd0d475f8006a.png)

![6e163ee6b82549120b4fe24aa2433bb](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（二）/6e163ee6b82549120b4fe24aa2433bb.png)

4. 证明该收敛的函数 <img src="https://www.zhihu.com/equation?tex=\phi(x)" alt="\phi(x)" class="ee_img tr_noresize" eeimg="1"> 是**唯一**的。
   ![7b2e0e679fd9164e0e7b47e9bcf6ef1](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（二）/7b2e0e679fd9164e0e7b47e9bcf6ef1.png)

需要注意的是，皮卡定理是**局部性的**。为了使定理成立的区域扩大，只需研究解的延拓问题。我们在定理成立的有界连续区域G内取一点 <img src="https://www.zhihu.com/equation?tex=P(x_0,y_0)" alt="P(x_0,y_0)" class="ee_img tr_noresize" eeimg="1"> 作为起点，过 <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> 的积分曲线上又能找到同样满足 <img src="https://www.zhihu.com/equation?tex=|x-x_0|\leqslant h" alt="|x-x_0|\leqslant h" class="ee_img tr_noresize" eeimg="1"> 的点，记 <img src="https://www.zhihu.com/equation?tex=x_1=x_0+h" alt="x_1=x_0+h" class="ee_img tr_noresize" eeimg="1"> ，那么又能找到一点 <img src="https://www.zhihu.com/equation?tex=P_1" alt="P_1" class="ee_img tr_noresize" eeimg="1"> ，由它可以继续在微分方程满足的区间内延拓，就像惠更斯定理一样。

##### 2. 一阶常微分方程组解的存在唯一性

考虑一阶常微分方程组

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
\frac{dy_1}{dx}=f_1(x,y_1,...,y_n) \\
............ \\
\frac{dy_n}{dx}=f_n(x,y_1,...,y_n)
\end{cases}
\tag{3}
" alt="\begin{cases}
\frac{dy_1}{dx}=f_1(x,y_1,...,y_n) \\
............ \\
\frac{dy_n}{dx}=f_n(x,y_1,...,y_n)
\end{cases}
\tag{3}
" class="ee_img tr_noresize" eeimg="1">
有初值条件： <img src="https://www.zhihu.com/equation?tex=x=x_0,y_i=y_i^0(i=1,2,...,n)" alt="x=x_0,y_i=y_i^0(i=1,2,...,n)" class="ee_img tr_noresize" eeimg="1"> 。若存在 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个可微函数

<img src="https://www.zhihu.com/equation?tex=y_1=\phi_1(x),...,y_n=\phi_n(x)
\tag{4}
" alt="y_1=\phi_1(x),...,y_n=\phi_n(x)
\tag{4}
" class="ee_img tr_noresize" eeimg="1">
满足方程组（3），那么（4）为微分方程组（3）的满足初值条件的特解。

**定理2**（与定理1类似，只不过变量变多了而已）
在闭合矩形区域 <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> 上， <img src="https://www.zhihu.com/equation?tex=R:|x-x_0|\leqslant a,|y_i-y_i^0|\leqslant b,(i=1,2,...,n)" alt="R:|x-x_0|\leqslant a,|y_i-y_i^0|\leqslant b,(i=1,2,...,n)" class="ee_img tr_noresize" eeimg="1"> ，函数 <img src="https://www.zhihu.com/equation?tex=f_i,\frac{\partial f_i}{\partial y_j}" alt="f_i,\frac{\partial f_i}{\partial y_j}" class="ee_img tr_noresize" eeimg="1"> 皆连续，那么方程组（3）在 <img src="https://www.zhihu.com/equation?tex=|x-x_0|\leqslant h" alt="|x-x_0|\leqslant h" class="ee_img tr_noresize" eeimg="1"> 上存在唯一解（4）满足初值条件。其中

<img src="https://www.zhihu.com/equation?tex=h=min(a,\frac{b}{M}),M=max{M_1,...,M_N},\\
M_i=max|f_i(x,y_1,...,y_n)|,i=1,2,...,n
\tag{5}
" alt="h=min(a,\frac{b}{M}),M=max{M_1,...,M_N},\\
M_i=max|f_i(x,y_1,...,y_n)|,i=1,2,...,n
\tag{5}
" class="ee_img tr_noresize" eeimg="1">

##### 3.  <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 阶微分方程解的存在唯一性

 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 阶微分方程的标准形式为

<img src="https://www.zhihu.com/equation?tex=y^{(n)}=f(x,y,y',...,y^{(n-1)})
\tag{6}
" alt="y^{(n)}=f(x,y,y',...,y^{(n-1)})
\tag{6}
" class="ee_img tr_noresize" eeimg="1">
初值条件：

<img src="https://www.zhihu.com/equation?tex=x=x_0,y=y_1^0,...,y^{(n-1)}=y_n^0
\tag{7}
" alt="x=x_0,y=y_1^0,...,y^{(n-1)}=y_n^0
\tag{7}
" class="ee_img tr_noresize" eeimg="1">
引入 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个新变量

<img src="https://www.zhihu.com/equation?tex=y_1=y,y_2=y',...,y_n=y^{(n-1)}
\tag{8}
" alt="y_1=y,y_2=y',...,y_n=y^{(n-1)}
\tag{8}
" class="ee_img tr_noresize" eeimg="1">
（6）可化为

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
\frac{dy_1}{dx}=y_2,\\
\frac{dy_2}{dx}=y_3,\\
.........\\
\frac{dy_{(n-1)}}{dx}=y_n,\\
\frac{dy_n}{dx}=f(x,y_1,y_2,...,y_n)
\end{cases}
\tag{9}
" alt="\begin{cases}
\frac{dy_1}{dx}=y_2,\\
\frac{dy_2}{dx}=y_3,\\
.........\\
\frac{dy_{(n-1)}}{dx}=y_n,\\
\frac{dy_n}{dx}=f(x,y_1,y_2,...,y_n)
\end{cases}
\tag{9}
" class="ee_img tr_noresize" eeimg="1">
初值条件化为

<img src="https://www.zhihu.com/equation?tex=x=x_0,y_1=y_1^0,...,y_n=y_n^0
\tag{10}
" alt="x=x_0,y_1=y_1^0,...,y_n=y_n^0
\tag{10}
" class="ee_img tr_noresize" eeimg="1">
**定理3**
![a7f7b68392abced894b3700134439e0](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/常微分方程笔记（二）/a7f7b68392abced894b3700134439e0.png)

###  <img src="https://www.zhihu.com/equation?tex=\S" alt="\S" class="ee_img tr_noresize" eeimg="1"> 4 未解出导数的一阶方程（一阶隐式方程）

一阶微分方程

<img src="https://www.zhihu.com/equation?tex=F(x,y,y')=0
\tag{11}
" alt="F(x,y,y')=0
\tag{11}
" class="ee_img tr_noresize" eeimg="1">
中未解出 <img src="https://www.zhihu.com/equation?tex=y'=f(x,y)" alt="y'=f(x,y)" class="ee_img tr_noresize" eeimg="1"> 。
利用引入适当参数的**参数化解法**求解。

##### 1.  <img src="https://www.zhihu.com/equation?tex=F(y')=0" alt="F(y')=0" class="ee_img tr_noresize" eeimg="1"> 型方程

设 <img src="https://www.zhihu.com/equation?tex=y'=K" alt="y'=K" class="ee_img tr_noresize" eeimg="1"> , <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> 为常数，那么 <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> 也是方程任意一个零点（至少有一个零点）。积分得

<img src="https://www.zhihu.com/equation?tex=y=Kx+c
\tag{12}
" alt="y=Kx+c
\tag{12}
" class="ee_img tr_noresize" eeimg="1">
从而解出 <img src="https://www.zhihu.com/equation?tex=K=(y-c)/x" alt="K=(y-c)/x" class="ee_img tr_noresize" eeimg="1"> ，带回方程可求解得隐式通解：

<img src="https://www.zhihu.com/equation?tex=F(\frac{y-c}{x})=0
\tag{13}
" alt="F(\frac{y-c}{x})=0
\tag{13}
" class="ee_img tr_noresize" eeimg="1">

##### 2.  <img src="https://www.zhihu.com/equation?tex=F(x,y')=0" alt="F(x,y')=0" class="ee_img tr_noresize" eeimg="1"> 型方程

引入参数 <img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1"> 使得

<img src="https://www.zhihu.com/equation?tex=x=\phi(t)\\
y'=\psi(t)
\tag{14}
" alt="x=\phi(t)\\
y'=\psi(t)
\tag{14}
" class="ee_img tr_noresize" eeimg="1">
从而有

<img src="https://www.zhihu.com/equation?tex=\frac{dy}{dt}=\frac{dy}{dx}\frac{dx}{dt}=\psi(t)\phi'(t)
\tag{15}
" alt="\frac{dy}{dt}=\frac{dy}{dx}\frac{dx}{dt}=\psi(t)\phi'(t)
\tag{15}
" class="ee_img tr_noresize" eeimg="1">
积分可得参数形式通解

<img src="https://www.zhihu.com/equation?tex=y=\int \psi(t)\phi'(t)dt+C
\tag{16}
" alt="y=\int \psi(t)\phi'(t)dt+C
\tag{16}
" class="ee_img tr_noresize" eeimg="1">

##### 3.  <img src="https://www.zhihu.com/equation?tex=F(y,y')=0" alt="F(y,y')=0" class="ee_img tr_noresize" eeimg="1"> 型方程

同样可以引入参数 <img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1"> 

<img src="https://www.zhihu.com/equation?tex=y=\phi(t)\\
y'=\psi(t)
\tag{17}
" alt="y=\phi(t)\\
y'=\psi(t)
\tag{17}
" class="ee_img tr_noresize" eeimg="1">
从而有

<img src="https://www.zhihu.com/equation?tex=\frac{dx}{dt}=\frac{dx}{dy}\frac{dy}{dt}= \frac{1}{y'}\frac{dy}{dt}=\frac{\phi'(t)}{\psi(t)}(y'\neq 0)
\tag{18}
" alt="\frac{dx}{dt}=\frac{dx}{dy}\frac{dy}{dt}= \frac{1}{y'}\frac{dy}{dt}=\frac{\phi'(t)}{\psi(t)}(y'\neq 0)
\tag{18}
" class="ee_img tr_noresize" eeimg="1">
从而积分得

<img src="https://www.zhihu.com/equation?tex=x=\int\frac{\phi'(t)}{\psi(t)}dt+C
\tag{19}
" alt="x=\int\frac{\phi'(t)}{\psi(t)}dt+C
\tag{19}
" class="ee_img tr_noresize" eeimg="1">
##### 4. 可就 <img src="https://www.zhihu.com/equation?tex=y" alt="y" class="ee_img tr_noresize" eeimg="1"> 解出的方程

对于方程 <img src="https://www.zhihu.com/equation?tex=y=f(x,y')" alt="y=f(x,y')" class="ee_img tr_noresize" eeimg="1"> ，可令 <img src="https://www.zhihu.com/equation?tex=y'=p" alt="y'=p" class="ee_img tr_noresize" eeimg="1"> ，那么方程变为

<img src="https://www.zhihu.com/equation?tex=y=f(x,p)
\tag{20}
" alt="y=f(x,p)
\tag{20}
" class="ee_img tr_noresize" eeimg="1">
求微分并利用  <img src="https://www.zhihu.com/equation?tex=\mathrm{d} y=p \mathrm{~d} x" alt="\mathrm{d} y=p \mathrm{~d} x" class="ee_img tr_noresize" eeimg="1"> , 得到

<img src="https://www.zhihu.com/equation?tex=\mathrm{d} y=p \mathrm{~d} x=\frac{\partial f}{\partial x} \mathrm{~d} x+\frac{\partial f}{\partial p} \mathrm{~d} p
\tag{21}
" alt="\mathrm{d} y=p \mathrm{~d} x=\frac{\partial f}{\partial x} \mathrm{~d} x+\frac{\partial f}{\partial p} \mathrm{~d} p
\tag{21}
" class="ee_img tr_noresize" eeimg="1">

整理即得  <img src="https://www.zhihu.com/equation?tex=x, p" alt="x, p" class="ee_img tr_noresize" eeimg="1">  的已解出导数的一阶方程

<img src="https://www.zhihu.com/equation?tex=\left(\frac{\partial f}{\partial c}-p\right) \mathrm{d} x+\frac{\partial f}{\partial p} \mathrm{~d} p=0 
\tag{22}
" alt="\left(\frac{\partial f}{\partial c}-p\right) \mathrm{d} x+\frac{\partial f}{\partial p} \mathrm{~d} p=0 
\tag{22}
" class="ee_img tr_noresize" eeimg="1">

若能求出方程（22）的通积分（通解）  <img src="https://www.zhihu.com/equation?tex=\Phi(x, p, c)=0, c" alt="\Phi(x, p, c)=0, c" class="ee_img tr_noresize" eeimg="1">  为任意常数, 则将它与方程（20）联列, 得到原微分方程的以  <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1">  为参数的通积分

<img src="https://www.zhihu.com/equation?tex=\left\{\begin{array}{l}
\Phi(x, p, c)=0 \\
y=f(x, p)
\end{array} \quad \text { ( } p\right. \text { 为参数) }
\tag{23}
" alt="\left\{\begin{array}{l}
\Phi(x, p, c)=0 \\
y=f(x, p)
\end{array} \quad \text { ( } p\right. \text { 为参数) }
\tag{23}
" class="ee_img tr_noresize" eeimg="1">

若式（23）可消去参数  <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> , 则得原方程的通积分  <img src="https://www.zhihu.com/equation?tex=F(x" alt="F(x" class="ee_img tr_noresize" eeimg="1"> ,  <img src="https://www.zhihu.com/equation?tex=y, c)=0" alt="y, c)=0" class="ee_img tr_noresize" eeimg="1"> . 例如, 若可从  <img src="https://www.zhihu.com/equation?tex=\Phi(x, p, c)=0" alt="\Phi(x, p, c)=0" class="ee_img tr_noresize" eeimg="1">  中解出  <img src="https://www.zhihu.com/equation?tex=p=\varphi(x, c)" alt="p=\varphi(x, c)" class="ee_img tr_noresize" eeimg="1"> , 将它代入  <img src="https://www.zhihu.com/equation?tex=y=f(x, p)" alt="y=f(x, p)" class="ee_img tr_noresize" eeimg="1"> , 即得原方程的通解为

<img src="https://www.zhihu.com/equation?tex=y=f(x, \varphi(x, c)) 
\tag{24}
" alt="y=f(x, \varphi(x, c)) 
\tag{24}
" class="ee_img tr_noresize" eeimg="1">

另外, 方程（22）可能有不含任意常数的解  <img src="https://www.zhihu.com/equation?tex=\Psi(x, p)=0" alt="\Psi(x, p)=0" class="ee_img tr_noresize" eeimg="1"> , 将它与式（20）联列得到以  <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1">  为参数表示的函数

<img src="https://www.zhihu.com/equation?tex=\left\{\begin{array}{l}
\Psi(x, p)=0 \\
y=f(x, p) 
\end{array}\right.
\tag{25}
" alt="\left\{\begin{array}{l}
\Psi(x, p)=0 \\
y=f(x, p) 
\end{array}\right.
\tag{25}
" class="ee_img tr_noresize" eeimg="1">

如果从  <img src="https://www.zhihu.com/equation?tex=\Psi(x, p)=0" alt="\Psi(x, p)=0" class="ee_img tr_noresize" eeimg="1">  又能解出  <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> , 代入  <img src="https://www.zhihu.com/equation?tex=y=f(x, p)" alt="y=f(x, p)" class="ee_img tr_noresize" eeimg="1">  得到函数

<img src="https://www.zhihu.com/equation?tex=y=\psi(x)
\tag{26}
" alt="y=\psi(x)
\tag{26}
" class="ee_img tr_noresize" eeimg="1">
若（26）满足原方程，且这个解通常不包含在通解中，称之为**奇解**。（看得不是很明白......可能看一下下面克莱罗方程的例子，会有一些feelings）

* **克莱罗方程**（Clairaut）

<img src="https://www.zhihu.com/equation?tex=y=xy'+\varphi(y')
  \tag{27}
  " alt="y=xy'+\varphi(y')
  \tag{27}
  " class="ee_img tr_noresize" eeimg="1">
  按照上面的方法，令 <img src="https://www.zhihu.com/equation?tex=y'=p" alt="y'=p" class="ee_img tr_noresize" eeimg="1"> ，得到

<img src="https://www.zhihu.com/equation?tex=y=xp+\varphi(p)
  \tag{28}
  " alt="y=xp+\varphi(p)
  \tag{28}
  " class="ee_img tr_noresize" eeimg="1">
  同理，取微分有

<img src="https://www.zhihu.com/equation?tex=pdx=pdx+xdp+\varphi'(p)dp
  \tag{29}
  " alt="pdx=pdx+xdp+\varphi'(p)dp
  \tag{29}
  " class="ee_img tr_noresize" eeimg="1">
  也即

<img src="https://www.zhihu.com/equation?tex=dp(x+\varphi'(p))=0
  \tag{30}
  " alt="dp(x+\varphi'(p))=0
  \tag{30}
  " class="ee_img tr_noresize" eeimg="1">

  * 由 <img src="https://www.zhihu.com/equation?tex=dp=0" alt="dp=0" class="ee_img tr_noresize" eeimg="1"> ，积分有 <img src="https://www.zhihu.com/equation?tex=p=C" alt="p=C" class="ee_img tr_noresize" eeimg="1"> ，代入（28）得方程的**通解**为


<img src="https://www.zhihu.com/equation?tex=y=Cx+\varphi(C)
  \tag{31}
  " alt="y=Cx+\varphi(C)
  \tag{31}
  " class="ee_img tr_noresize" eeimg="1">

  * 由 <img src="https://www.zhihu.com/equation?tex=x+\varphi'(p)=0" alt="x+\varphi'(p)=0" class="ee_img tr_noresize" eeimg="1"> ，代入（28），再将 <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> 换成参数 <img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1"> （此处这样代换应该是为了避免符号相同引起歧义）

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
    x=-\varphi'(t)\\
    y=-t\varphi'(t)+\varphi(t)
    \end{cases}
    \tag{32}
    " alt="\begin{cases}
    x=-\varphi'(t)\\
    y=-t\varphi'(t)+\varphi(t)
    \end{cases}
    \tag{32}
    " class="ee_img tr_noresize" eeimg="1">
    这就是方程的**奇解**。
    可证明是奇解是方程的解，由（32）式可以求得

<img src="https://www.zhihu.com/equation?tex=\frac{dy}{dx}=\frac{-\varphi'(t)-t\varphi''(t)+\varphi'(t)}{-\varphi''(t)}=t
    \tag{33}
    " alt="\frac{dy}{dx}=\frac{-\varphi'(t)-t\varphi''(t)+\varphi'(t)}{-\varphi''(t)}=t
    \tag{33}
    " class="ee_img tr_noresize" eeimg="1">
    带回原方程（27），可证得等式两边恒等。
    另外发现，曲线在 <img src="https://www.zhihu.com/equation?tex=t=C" alt="t=C" class="ee_img tr_noresize" eeimg="1"> 处切线的斜率就是 <img src="https://www.zhihu.com/equation?tex=C" alt="C" class="ee_img tr_noresize" eeimg="1"> ，切线方程为 <img src="https://www.zhihu.com/equation?tex=y=Cx+\varphi(C)" alt="y=Cx+\varphi(C)" class="ee_img tr_noresize" eeimg="1"> ，而前面的通解是一直线族 <img src="https://www.zhihu.com/equation?tex=y=Cx+\varphi(C)" alt="y=Cx+\varphi(C)" class="ee_img tr_noresize" eeimg="1"> ，所以**克莱罗方程的奇解曲线就是通解直线族的包络**。

##### 5. 可就 <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> 解出的方程

对于方程 <img src="https://www.zhihu.com/equation?tex=x=f(y,p),\quad (p=y')" alt="x=f(y,p),\quad (p=y')" class="ee_img tr_noresize" eeimg="1"> ，可以用上面类似的方法解决。两边微分得到

<img src="https://www.zhihu.com/equation?tex=dx=f'_ydy+f'_pdp
\tag{34}
" alt="dx=f'_ydy+f'_pdp
\tag{34}
" class="ee_img tr_noresize" eeimg="1">
再代入微分 <img src="https://www.zhihu.com/equation?tex=dy=pdx" alt="dy=pdx" class="ee_img tr_noresize" eeimg="1"> ，可以得到

<img src="https://www.zhihu.com/equation?tex=(1-pf_y')dy-pf_p'dp=0
\tag{35}
" alt="(1-pf_y')dy-pf_p'dp=0
\tag{35}
" class="ee_img tr_noresize" eeimg="1">
同理可求出方程（35）的通积分 <img src="https://www.zhihu.com/equation?tex=\Phi(y,p,c)=0" alt="\Phi(y,p,c)=0" class="ee_img tr_noresize" eeimg="1"> ，那么原方程的通积分为

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
\Phi(y,p,c)=0\\
x=f(y,p)
\end{cases}
\quad \text{(p为参数)}
\tag{36}
" alt="\begin{cases}
\Phi(y,p,c)=0\\
x=f(y,p)
\end{cases}
\quad \text{(p为参数)}
\tag{36}
" class="ee_img tr_noresize" eeimg="1">
同样的，如果方程（35）有个别解 <img src="https://www.zhihu.com/equation?tex=\Psi(y,p)=0" alt="\Psi(y,p)=0" class="ee_img tr_noresize" eeimg="1"> ，那么与原方程联立后，可以得到以 <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> 为参数的函数

<img src="https://www.zhihu.com/equation?tex=\begin{cases}
\Psi(y,p)=0\\
x=f(y,p)
\end{cases}
\tag{37}
" alt="\begin{cases}
\Psi(y,p)=0\\
x=f(y,p)
\end{cases}
\tag{37}
" class="ee_img tr_noresize" eeimg="1">
这可能是方程的奇解。