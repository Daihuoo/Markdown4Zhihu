# 天体力学

### 一，椭圆轨道

#### 1，开普勒行星运动定律

开普勒继承了第谷观测得到的大量数据，并且开始极为艰苦的数据分析。起初，开普勒设计了一套精确的围绕太阳的圆形轨道，最终得到的结果与第谷数据相当吻合。但是有两个点除外，且每一个都偏差了 <img src="https://www.zhihu.com/equation?tex=8'" alt="8'" class="ee_img tr_noresize" eeimg="1"> ，这是数据精度的两倍，因此开普勒摈弃了纯圆周运动的想法。

进一步，开普勒开始考虑椭圆轨道运动。这一相对较小的数学变化，在当时的历史背景下，却是哲学上的一大步变化。最终开普勒得到了与第谷所有观测数据一致的结果。

1609年，开普勒在 *Astronomia Nova* 一书中发表了行星运动定律的前两条。十年后，在 *Harmonica Mundi* 一书中，发表了第三定律。

* 开普勒第一定律：行星以椭圆轨道围绕太阳运动，太阳在椭圆的一个焦点上。

* 开普勒第二定律：行星和太阳的连线在相等的时间间隔内扫出的面积相等。

* 开普勒第三定律：行星运动轨道半长轴的立方与运动周期的平方之比为常数。即调和定律：

<img src="https://www.zhihu.com/equation?tex=P^2=a^3
  \tag{1}
  " alt="P^2=a^3
  \tag{1}
  " class="ee_img tr_noresize" eeimg="1">

其中 <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> 是行星的公转轨道周期，以年为单位； <img src="https://www.zhihu.com/equation?tex=a" alt="a" class="ee_img tr_noresize" eeimg="1"> 是行星到太阳的平均距离，以天文单位AU为单位。一个天文单位是地球与太阳之间的平均距离，约为1.5亿公里。

![太阳系内天体遵循开普勒第三定律](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240729101119525.png)

#### 2，椭圆运动几何学

我们知道椭圆的第一定义为：椭圆上任何一点到两个焦点的距离之和为常数，即有：

<img src="https://www.zhihu.com/equation?tex=r+r'=2a
\tag{2}
" alt="r+r'=2a
\tag{2}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=a" alt="a" class="ee_img tr_noresize" eeimg="1"> 为椭圆的**半长轴**（semimajor axis），即椭圆长轴或主轴长度的一半； <img src="https://www.zhihu.com/equation?tex=r,r'" alt="r,r'" class="ee_img tr_noresize" eeimg="1"> 分别为椭圆上任意一点到两个**焦点**（focal point） <img src="https://www.zhihu.com/equation?tex=F,F'" alt="F,F'" class="ee_img tr_noresize" eeimg="1"> 的距离。对于行星的轨道运动，太阳位于一个**主焦点**（primary focus）上，另一个焦点上没有天体。定义**短轴**（semiminor axis）： <img src="https://www.zhihu.com/equation?tex=b" alt="b" class="ee_img tr_noresize" eeimg="1"> 。定义**偏心率**（eccentricity） <img src="https://www.zhihu.com/equation?tex=e" alt="e" class="ee_img tr_noresize" eeimg="1"> （ <img src="https://www.zhihu.com/equation?tex=0\leq e< 1" alt="0\leq e< 1" class="ee_img tr_noresize" eeimg="1"> ）为两个焦点之间的距离（ <img src="https://www.zhihu.com/equation?tex=2c" alt="2c" class="ee_img tr_noresize" eeimg="1"> ）与长轴的比值，即

<img src="https://www.zhihu.com/equation?tex=e=\frac{c}{a}
\tag{3}
" alt="e=\frac{c}{a}
\tag{3}
" class="ee_img tr_noresize" eeimg="1">
椭圆上离主焦点最近的点为**近日点**（perihelion），反之为**远日点**（aphelion），它们分别在长轴的两端。

椭圆长轴，短轴与偏心率有几何关系：

<img src="https://www.zhihu.com/equation?tex=b^2=a^2(1-e^2)
\tag{4}
" alt="b^2=a^2(1-e^2)
\tag{4}
" class="ee_img tr_noresize" eeimg="1">
![椭圆几何示意图](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240729102309214.png)

由上图，根据勾股定理有：

<img src="https://www.zhihu.com/equation?tex=r'^2=r^2\sin^2\theta+(2ae+r\cos\theta)^2
\tag{5}
" alt="r'^2=r^2\sin^2\theta+(2ae+r\cos\theta)^2
\tag{5}
" class="ee_img tr_noresize" eeimg="1">
再由(2)消去 <img src="https://www.zhihu.com/equation?tex=r'" alt="r'" class="ee_img tr_noresize" eeimg="1"> ，得到：

<img src="https://www.zhihu.com/equation?tex=r=\frac{a(1-e^2)}{1+e\cos\theta} \quad (0\leq e <1)
\tag{6}
" alt="r=\frac{a(1-e^2)}{1+e\cos\theta} \quad (0\leq e <1)
\tag{6}
" class="ee_img tr_noresize" eeimg="1">
由微积分的知识，可以对椭圆方程进行积分，得到椭圆面积公式：

<img src="https://www.zhihu.com/equation?tex=A=\pi ab
\tag{7}
" alt="A=\pi ab
\tag{7}
" class="ee_img tr_noresize" eeimg="1">
我们知道椭圆其实是圆锥曲线的一种，每一种圆锥曲线对应着不同的偏心率范围。例如圆是 <img src="https://www.zhihu.com/equation?tex=e=0" alt="e=0" class="ee_img tr_noresize" eeimg="1"> 的圆锥曲线。抛物线是 <img src="https://www.zhihu.com/equation?tex=e=1" alt="e=1" class="ee_img tr_noresize" eeimg="1"> 的圆锥曲线：

<img src="https://www.zhihu.com/equation?tex=r=\frac{2p}{1+\cos\theta}
\tag{8}
" alt="r=\frac{2p}{1+\cos\theta}
\tag{8}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> 是 <img src="https://www.zhihu.com/equation?tex=\theta=0" alt="\theta=0" class="ee_img tr_noresize" eeimg="1"> 时，距抛物线焦点最近的距离。双曲线是 <img src="https://www.zhihu.com/equation?tex=e>1" alt="e>1" class="ee_img tr_noresize" eeimg="1"> 的圆锥曲线，即有：

<img src="https://www.zhihu.com/equation?tex=r=\frac{a(e^2-1)}{1+e\cos\theta}\quad (e>1)
\tag{9}
" alt="r=\frac{a(e^2-1)}{1+e\cos\theta}\quad (e>1)
\tag{9}
" class="ee_img tr_noresize" eeimg="1">
每一种圆锥曲线都对应一种天体运动形式。

### 二，牛顿力学

#### 1，牛顿三定律

* **牛顿第一定律**：**惯性定律**。静止的物体将保持静止，运动的物体将保持在一条直线上以恒定的速度运动，除非受到外力的作用。判断物体是否在运动，需要借助**惯性参考系**（inertial reference frames）。牛顿第一定律也可以用动量描述：

<img src="https://www.zhihu.com/equation?tex=\mathbf{p}=m\mathbf{v}
  \tag{10}
  " alt="\mathbf{p}=m\mathbf{v}
  \tag{10}
  " class="ee_img tr_noresize" eeimg="1">
  即物体的动量保持不变，除非受到力的作用。

* 牛顿第二定律：作用在物体上的合力与物体的质量和加速度成正比。

<img src="https://www.zhihu.com/equation?tex=\mathbf{F_{net}}=\sum_{i=1}^{n}\mathbf{F_i}=m\mathbf{a}
  \tag{11}
  " alt="\mathbf{F_{net}}=\sum_{i=1}^{n}\mathbf{F_i}=m\mathbf{a}
  \tag{11}
  " class="ee_img tr_noresize" eeimg="1">
  由加速度的定义，可以得到：

<img src="https://www.zhihu.com/equation?tex=\mathbf{F_{net}}=m\frac{d\mathbf{v}}{dt}=\frac{d(m\mathbf{v})}{dt}=\frac{d\mathbf{p}}{dt}
  \tag{12}
  " alt="\mathbf{F_{net}}=m\frac{d\mathbf{v}}{dt}=\frac{d(m\mathbf{v})}{dt}=\frac{d\mathbf{p}}{dt}
  \tag{12}
  " class="ee_img tr_noresize" eeimg="1">
  即，一个物体所受合力等于其动量的时间变化率。

* 牛顿第三定律：每一个作用力都有一个与之大小相等且方向相反的作用力。

<img src="https://www.zhihu.com/equation?tex=\mathbf{F_{12}}=-\mathbf{F_{21}}
  \tag{13}
  " alt="\mathbf{F_{12}}=-\mathbf{F_{21}}
  \tag{13}
  " class="ee_img tr_noresize" eeimg="1">

#### 2，万有引力定律

我们可以由开普勒行星运动三定律和牛顿三定律推出万有引力定律的公式。开普勒第三定律可以写为：

<img src="https://www.zhihu.com/equation?tex=P^2=kr^3
\tag{14}
" alt="P^2=kr^3
\tag{14}
" class="ee_img tr_noresize" eeimg="1">
同时轨道周期可以写为：

<img src="https://www.zhihu.com/equation?tex=P=\frac{2\pi}{w}=\frac{2\pi r}{v}
\tag{15}
" alt="P=\frac{2\pi}{w}=\frac{2\pi r}{v}
\tag{15}
" class="ee_img tr_noresize" eeimg="1">
联立(14)(15)，得：

<img src="https://www.zhihu.com/equation?tex=\frac{4\pi^2 r^2}{v^2}=kr^3
\tag{16}
" alt="\frac{4\pi^2 r^2}{v^2}=kr^3
\tag{16}
" class="ee_img tr_noresize" eeimg="1">
两边可同时乘以质量 <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> ，并考虑向心力公式，得：

<img src="https://www.zhihu.com/equation?tex=F=m\frac{v^2}{r}=\frac{4\pi^2 m}{kr^2}
\tag{17}
" alt="F=m\frac{v^2}{r}=\frac{4\pi^2 m}{kr^2}
\tag{17}
" class="ee_img tr_noresize" eeimg="1">
而根据牛顿第三定律， <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> 对 <img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1"> 施加的力应与 <img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1"> 对 <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> 施加的力大小相等，即：

<img src="https://www.zhihu.com/equation?tex=F=\frac{4\pi^2 m}{kr^2}=\frac{4\pi^2 M}{k'r^2}
\tag{18}
" alt="F=\frac{4\pi^2 m}{kr^2}=\frac{4\pi^2 M}{k'r^2}
\tag{18}
" class="ee_img tr_noresize" eeimg="1">
则可改写为：

<img src="https://www.zhihu.com/equation?tex=F=\frac{4\pi^2 Mm}{k''r^2}=G\frac{Mm}{r^2}
\tag{19}
" alt="F=\frac{4\pi^2 Mm}{k''r^2}=G\frac{Mm}{r^2}
\tag{19}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=G=6.673\times 10^{-11}N\cdot m^2\cdot kg^{-2}" alt="G=6.673\times 10^{-11}N\cdot m^2\cdot kg^{-2}" class="ee_img tr_noresize" eeimg="1"> 定义为万有引力常数。

> 例. 球对称物体的引力作用
>
> ![球对称质量分布的引力效应](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240729132340034.png)
>
> 设环的质量为 <img src="https://www.zhihu.com/equation?tex=dM_{ring}" alt="dM_{ring}" class="ee_img tr_noresize" eeimg="1"> ，则其对 <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> 施加的引力为：

<img src="https://www.zhihu.com/equation?tex=> dF_{ring}=G\frac{mdM_{ring}}{s^2}\cos\phi
> \tag{20}
> " alt="> dF_{ring}=G\frac{mdM_{ring}}{s^2}\cos\phi
> \tag{20}
> " class="ee_img tr_noresize" eeimg="1">
> 其中 <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1"> 是 <img src="https://www.zhihu.com/equation?tex=s" alt="s" class="ee_img tr_noresize" eeimg="1"> 与 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 的夹角。这里乘上余弦因子是因为力在垂直于 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 方向上的分量相互抵消了。假设物体密度是半径的函数 <img src="https://www.zhihu.com/equation?tex=\rho(R)" alt="\rho(R)" class="ee_img tr_noresize" eeimg="1"> ，那么环的质量可以写为：

<img src="https://www.zhihu.com/equation?tex=> \begin{aligned}
> dM_{ring}&=\rho(R)dV_{ring}\\
> &=\rho(R)2\pi R^2\sin\theta d\theta dR
> \end{aligned}
> \tag{21}
> " alt="> \begin{aligned}
> dM_{ring}&=\rho(R)dV_{ring}\\
> &=\rho(R)2\pi R^2\sin\theta d\theta dR
> \end{aligned}
> \tag{21}
> " class="ee_img tr_noresize" eeimg="1">
> 余弦计算公式为：

<img src="https://www.zhihu.com/equation?tex=> \cos\phi=\frac{r-R\cos\theta}{s}
> \tag{22}
> " alt="> \cos\phi=\frac{r-R\cos\theta}{s}
> \tag{22}
> " class="ee_img tr_noresize" eeimg="1">
> 其中 <img src="https://www.zhihu.com/equation?tex=s" alt="s" class="ee_img tr_noresize" eeimg="1"> 可以由勾股定理写出：

<img src="https://www.zhihu.com/equation?tex=> s=\sqrt{(r-R\cos\theta)^2+R^2\sin^2\theta}=\sqrt{r^2-2rR\cos\theta+R^2}
> \tag{23}
> " alt="> s=\sqrt{(r-R\cos\theta)^2+R^2\sin^2\theta}=\sqrt{r^2-2rR\cos\theta+R^2}
> \tag{23}
> " class="ee_img tr_noresize" eeimg="1">
> 将上面的式子代入(20)，并且对 <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> 和 <img src="https://www.zhihu.com/equation?tex=\theta" alt="\theta" class="ee_img tr_noresize" eeimg="1"> 积分，有：

<img src="https://www.zhihu.com/equation?tex=> F=Gm\int_0^{R_0}\int_0^\pi\frac{(r-R\cos\theta)\rho(R)2\pi^2R^2\sin\theta}{s^3}d\theta dR
> \tag{24}
> " alt="> F=Gm\int_0^{R_0}\int_0^\pi\frac{(r-R\cos\theta)\rho(R)2\pi^2R^2\sin\theta}{s^3}d\theta dR
> \tag{24}
> " class="ee_img tr_noresize" eeimg="1">
> 经过一系列的推导，最终得到：

<img src="https://www.zhihu.com/equation?tex=> F=\frac{Gm}{r^2}\int_0^{R_0}4\pi R^2\rho(R)dR
> \tag{25}
> " alt="> F=\frac{Gm}{r^2}\int_0^{R_0}4\pi R^2\rho(R)dR
> \tag{25}
> " class="ee_img tr_noresize" eeimg="1">
> 其中积分即 <img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1"> 。

假如物体在距离地球表面 <img src="https://www.zhihu.com/equation?tex=h" alt="h" class="ee_img tr_noresize" eeimg="1"> 高处，其受到的力为：

<img src="https://www.zhihu.com/equation?tex=F=G\frac{Mm}{(R+h)^2}
\tag{26}
" alt="F=G\frac{Mm}{(R+h)^2}
\tag{26}
" class="ee_img tr_noresize" eeimg="1">
当 <img src="https://www.zhihu.com/equation?tex=h\ll R" alt="h\ll R" class="ee_img tr_noresize" eeimg="1"> 时，并由加速度公式，则有：

<img src="https://www.zhihu.com/equation?tex=g=G\frac{M}{R^2}\approx 9.8\times m\cdot s^{-2}
\tag{27}
" alt="g=G\frac{M}{R^2}\approx 9.8\times m\cdot s^{-2}
\tag{27}
" class="ee_img tr_noresize" eeimg="1">

#### 3，功和能量

在引力作用下，将质量 <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> 的物体提升至高度 <img src="https://www.zhihu.com/equation?tex=h" alt="h" class="ee_img tr_noresize" eeimg="1"> 所需要的能量等于系统势能的变化量。即有：

<img src="https://www.zhihu.com/equation?tex=U_f-U_i=\Delta U=-\mathbf{\int_{r_i}^{r_f}F\cdot dr}
\tag{28}
" alt="U_f-U_i=\Delta U=-\mathbf{\int_{r_i}^{r_f}F\cdot dr}
\tag{28}
" class="ee_img tr_noresize" eeimg="1">
由于引力与位矢方向相反，即有 <img src="https://www.zhihu.com/equation?tex=\mathbf{F\cdot dr}=-Fdr" alt="\mathbf{F\cdot dr}=-Fdr" class="ee_img tr_noresize" eeimg="1"> ，则：

<img src="https://www.zhihu.com/equation?tex=\Delta U=\int_{r_i}^{r_f}F\frac{Mm}{r^2}dr=-GMm(\frac{1}{r_f}-\frac{1}{r_i})
\tag{29}
" alt="\Delta U=\int_{r_i}^{r_f}F\frac{Mm}{r^2}dr=-GMm(\frac{1}{r_f}-\frac{1}{r_i})
\tag{29}
" class="ee_img tr_noresize" eeimg="1">
假设无限远处势能为0，则令 <img src="https://www.zhihu.com/equation?tex=r_i\rightarrow \infty" alt="r_i\rightarrow \infty" class="ee_img tr_noresize" eeimg="1"> ，有：

<img src="https://www.zhihu.com/equation?tex=U=-G\frac{Mm}{r}
\tag{30}
" alt="U=-G\frac{Mm}{r}
\tag{30}
" class="ee_img tr_noresize" eeimg="1">
反过来，引力即引力势能的导数，即：

<img src="https://www.zhihu.com/equation?tex=F=-\frac{\partial U}{\partial r}
\tag{31}
" alt="F=-\frac{\partial U}{\partial r}
\tag{31}
" class="ee_img tr_noresize" eeimg="1">
改变速度，需要对物体做功。我们有：

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
W&\equiv -\Delta U\\
&=\mathbf{\int_{r_i}^{r_f}F\cdot dr}\\
&=\int_{\mathbf{r_i}}^{\mathbf{r_f}}\frac{d\mathbf{p}}{dr}\cdot(\mathbf{v}dt)\\
&=\int_{\mathbf{t_i}}^{\mathbf{t_f}}m(\mathbf{v}\cdot \frac{d\mathbf{v}}{dt})dt \\
&=\int_{v_i}^{v_f}md(\frac{1}{2}v^2)\\
&=\frac{1}{2}mv_f^2-\frac{1}{2}mv_i^2
\end{aligned}
\tag{32}
" alt="\begin{aligned}
W&\equiv -\Delta U\\
&=\mathbf{\int_{r_i}^{r_f}F\cdot dr}\\
&=\int_{\mathbf{r_i}}^{\mathbf{r_f}}\frac{d\mathbf{p}}{dr}\cdot(\mathbf{v}dt)\\
&=\int_{\mathbf{t_i}}^{\mathbf{t_f}}m(\mathbf{v}\cdot \frac{d\mathbf{v}}{dt})dt \\
&=\int_{v_i}^{v_f}md(\frac{1}{2}v^2)\\
&=\frac{1}{2}mv_f^2-\frac{1}{2}mv_i^2
\end{aligned}
\tag{32}
" class="ee_img tr_noresize" eeimg="1">
由此定义动能（kinetic energy）：

<img src="https://www.zhihu.com/equation?tex=K=\frac{1}{2}mv^2
\tag{33}
" alt="K=\frac{1}{2}mv^2
\tag{33}
" class="ee_img tr_noresize" eeimg="1">
物体的总能量可以写为：

<img src="https://www.zhihu.com/equation?tex=E=\frac{1}{2}mv^2-G\frac{Mm}{r}
\tag{34}
" alt="E=\frac{1}{2}mv^2-G\frac{Mm}{r}
\tag{34}
" class="ee_img tr_noresize" eeimg="1">
在临界状态，质点的总能量在任何时刻为0：

<img src="https://www.zhihu.com/equation?tex=\frac{1}{2}mv^2=G\frac{Mm}{r}
\tag{34}
" alt="\frac{1}{2}mv^2=G\frac{Mm}{r}
\tag{34}
" class="ee_img tr_noresize" eeimg="1">
由此可求出逃逸速度，即不再受到引力束缚所需要的速度：

<img src="https://www.zhihu.com/equation?tex=v_{esc}=\sqrt{2GM/r}
\tag{35}
" alt="v_{esc}=\sqrt{2GM/r}
\tag{35}
" class="ee_img tr_noresize" eeimg="1">

### 三，开普勒定律的推导

开普勒是通过行星大量的观测数据得到的运动定律，但无法解释为何行星以这样的轨道运动。但牛顿提出的理论可以解释行星运动的经验定律。

#### 1，质心参考系

![笛卡尔坐标系](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240730095903376.png)

有着相互作用的二体问题或多体问题更容易在质心参考系中体现。上图中给出了质量分别为 <img src="https://www.zhihu.com/equation?tex=m_1,m_2" alt="m_1,m_2" class="ee_img tr_noresize" eeimg="1"> 的物体，其位矢分别为 <img src="https://www.zhihu.com/equation?tex=\mathbf{r_1',r_2'}" alt="\mathbf{r_1',r_2'}" class="ee_img tr_noresize" eeimg="1"> ，其质心位于 <img src="https://www.zhihu.com/equation?tex=\mathbf{R}" alt="\mathbf{R}" class="ee_img tr_noresize" eeimg="1"> 处，定义：

<img src="https://www.zhihu.com/equation?tex=\mathbf{r=r_2'-r_1'}
\tag{36}
" alt="\mathbf{r=r_2'-r_1'}
\tag{36}
" class="ee_img tr_noresize" eeimg="1">


<img src="https://www.zhihu.com/equation?tex=\mathbf{R}\equiv \frac{m_1\mathbf{r_1'}+m_2\mathbf{r_2'}}{m_1+m_2}
\tag{37}
" alt="\mathbf{R}\equiv \frac{m_1\mathbf{r_1'}+m_2\mathbf{r_2'}}{m_1+m_2}
\tag{37}
" class="ee_img tr_noresize" eeimg="1">

对于 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 个物体，有：

<img src="https://www.zhihu.com/equation?tex=\mathbf{R}\equiv \frac{\sum_{i=1}^n m_i\mathbf{r_i'}}{\sum_{i=1}^n m_i}
\tag{38}
" alt="\mathbf{R}\equiv \frac{\sum_{i=1}^n m_i\mathbf{r_i'}}{\sum_{i=1}^n m_i}
\tag{38}
" class="ee_img tr_noresize" eeimg="1">
定义总质量 <img src="https://www.zhihu.com/equation?tex=M=\sum_{i=1}^n" alt="M=\sum_{i=1}^n" class="ee_img tr_noresize" eeimg="1"> ，则有：

<img src="https://www.zhihu.com/equation?tex=M\mathbf{R}=\sum_{i=1}^n m_i\mathbf{r_i'}
\tag{39}
" alt="M\mathbf{R}=\sum_{i=1}^n m_i\mathbf{r_i'}
\tag{39}
" class="ee_img tr_noresize" eeimg="1">
假设物体质量不发生变化，则两边同时对位矢求时间的导数，有：

<img src="https://www.zhihu.com/equation?tex=M\frac{d\mathbf{R}}{dt}=\sum_{i=1}^n m_i\frac{d\mathbf{r_i'}}{dt}
\tag{40}
" alt="M\frac{d\mathbf{R}}{dt}=\sum_{i=1}^n m_i\frac{d\mathbf{r_i'}}{dt}
\tag{40}
" class="ee_img tr_noresize" eeimg="1">
即：

<img src="https://www.zhihu.com/equation?tex=M\mathbf{V}=\sum_{i=1}^n m_i\mathbf{v_i'}
\tag{41}
" alt="M\mathbf{V}=\sum_{i=1}^n m_i\mathbf{v_i'}
\tag{41}
" class="ee_img tr_noresize" eeimg="1">
等式左右两边分别是质心动量和各分量动量之和，即：

<img src="https://www.zhihu.com/equation?tex=\mathbf{P=\sum_{i=1}^n p_i'}
\tag{42}
" alt="\mathbf{P=\sum_{i=1}^n p_i'}
\tag{42}
" class="ee_img tr_noresize" eeimg="1">
两边再次同时对时间求导，得到力的表达式：

<img src="https://www.zhihu.com/equation?tex=\mathbf{F}=\frac{d\mathbf{P}}{dt}=M\frac{d^2\mathbf{R}}{dt^2}=0
\tag{43}
" alt="\mathbf{F}=\frac{d\mathbf{P}}{dt}=M\frac{d^2\mathbf{R}}{dt^2}=0
\tag{43}
" class="ee_img tr_noresize" eeimg="1">
这是因为根据牛顿第三定律，系统的总合力应为零。于是在无外力作用下，质心参考系是惯性参考系，研究二体或多体问题可以选取质心参考系，令 <img src="https://www.zhihu.com/equation?tex=\mathbf{R}=0" alt="\mathbf{R}=0" class="ee_img tr_noresize" eeimg="1"> ，来简化问题。于是(37)可以写为：

<img src="https://www.zhihu.com/equation?tex=\frac{m_1\mathbf{r_1}+m_2\mathbf{r_2}}{m_1+m_2}=0
\tag{44}
" alt="\frac{m_1\mathbf{r_1}+m_2\mathbf{r_2}}{m_1+m_2}=0
\tag{44}
" class="ee_img tr_noresize" eeimg="1">
再由：

<img src="https://www.zhihu.com/equation?tex=\mathbf{r=r_2-r_1}
\tag{45}
" alt="\mathbf{r=r_2-r_1}
\tag{45}
" class="ee_img tr_noresize" eeimg="1">
可得到如下关系：

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
& \mathbf{r_1}=-\frac{m_2}{m_1+m_2}\mathbf{r} \\
& \mathbf{r_2}=\frac{m_1}{m_1+m_2}\mathbf{r}
\end{aligned}
\tag{46}
" alt="\begin{aligned}
& \mathbf{r_1}=-\frac{m_2}{m_1+m_2}\mathbf{r} \\
& \mathbf{r_2}=\frac{m_1}{m_1+m_2}\mathbf{r}
\end{aligned}
\tag{46}
" class="ee_img tr_noresize" eeimg="1">
同时，可定义**折合质量**（reduced mass）：

<img src="https://www.zhihu.com/equation?tex=\mu\equiv \frac{m_1m_2}{m_1+m_2}
\tag{47}
" alt="\mu\equiv \frac{m_1m_2}{m_1+m_2}
\tag{47}
" class="ee_img tr_noresize" eeimg="1">
![质心参考系](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240730105806551.png)

于是坐标可以改写为：

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
& \mathbf{r_1}=-\frac{\mu}{m_1}\mathbf{r} \\
& \mathbf{r_2}=\frac{\mu}{m_2}\mathbf{r}
\end{aligned}
\tag{48}
" alt="\begin{aligned}
& \mathbf{r_1}=-\frac{\mu}{m_1}\mathbf{r} \\
& \mathbf{r_2}=\frac{\mu}{m_2}\mathbf{r}
\end{aligned}
\tag{48}
" class="ee_img tr_noresize" eeimg="1">
同样能量也可以改写为质心坐标系下的表达式：

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
E&=\frac{1}{2}m_1\mathbf{|v_1|}^2+\frac{1}{2}m_2\mathbf{|v_2|}^2-G\frac{m_1m_2}{|\mathbf{r_2-r_1}|}\\
&=\frac{1}{2}\mu v^2-G\frac{M\mu}{r}
\end{aligned}
\tag{49}
" alt="\begin{aligned}
E&=\frac{1}{2}m_1\mathbf{|v_1|}^2+\frac{1}{2}m_2\mathbf{|v_2|}^2-G\frac{m_1m_2}{|\mathbf{r_2-r_1}|}\\
&=\frac{1}{2}\mu v^2-G\frac{M\mu}{r}
\end{aligned}
\tag{49}
" class="ee_img tr_noresize" eeimg="1">
其中， <img src="https://www.zhihu.com/equation?tex=v=|\mathbf{v}|=|d\mathbf{r}/dt|" alt="v=|\mathbf{v}|=|d\mathbf{r}/dt|" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=r=|\mathbf{r_2-r_1}|" alt="r=|\mathbf{r_2-r_1}|" class="ee_img tr_noresize" eeimg="1"> 。

同样轨道角动量也可以改写：

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
\mathbf{L}&=m_1\mathbf{r_1}\times \mathbf{v_1}+m_2\mathbf{r_2}\times \mathbf{v_2}\\
&=\mu \mathbf{r}\times \mathbf{v}=\mathbf{r\times p}
\end{aligned}
\tag{50}
" alt="\begin{aligned}
\mathbf{L}&=m_1\mathbf{r_1}\times \mathbf{v_1}+m_2\mathbf{r_2}\times \mathbf{v_2}\\
&=\mu \mathbf{r}\times \mathbf{v}=\mathbf{r\times p}
\end{aligned}
\tag{50}
" class="ee_img tr_noresize" eeimg="1">
其中， <img src="https://www.zhihu.com/equation?tex=\mathbf{p}=\mu\times \mathbf{v}" alt="\mathbf{p}=\mu\times \mathbf{v}" class="ee_img tr_noresize" eeimg="1"> 。

*由于后续推导公式较多，故偷懒用手写代替。*

#### 2，开普勒第一定律的推导

![开普勒第一定律推导1](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240730132720468.png)

![开普勒第一定律推导2](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240730132727594.png)

#### 3，开普勒第二定律的推导

![开普勒第二定律推导1](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240730132735255.png)

![开普勒第二定律推导2](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240730132742641.png)

#### 4，开普勒第三定律的推导

![开普勒第三定律推导](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240730132750560.png)

### 四，位力定理

对于处于平衡状态的引力约束系统，其总能量是时间平均势能的一半，即**位力定理**（virial theorem）

位力定理的证明：

![位力定理证明推导1](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240730135108648.png)

![位力定理证明推导2](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第2章-天体力学/image-20240730135128317.png)
