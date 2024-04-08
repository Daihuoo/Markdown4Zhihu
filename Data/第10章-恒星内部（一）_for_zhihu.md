# 第10章 恒星内部（一）

对各种望远镜收集到的星光进行分析，我们可以较为容易地确定与恒星外层相关的各种物理量，例如有效温度，光度，元素组成等等。但是想要确认恒星内部的结构却十分困难。除了少数几种能直接探测到恒星内部的技术（例如探测太阳中微子），更多得需要我们建立恒星结构与演化的计算模型。

### 一，流体静力学平衡 Hydrostatic Equilibrium

##### 1. 流体静力学平衡公式

在恒星内部，与**引力**相抗衡的力是**压强**提供的。考虑距离恒星中心 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 处的一个圆柱体，设其底面积为 <img src="https://www.zhihu.com/equation?tex=\mathrm{d}A" alt="\mathrm{d}A" class="ee_img tr_noresize" eeimg="1"> ，厚度为 <img src="https://www.zhihu.com/equation?tex=\mathrm{d}r" alt="\mathrm{d}r" class="ee_img tr_noresize" eeimg="1"> ，如下图：

![image-20240405091235370](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/流体静力学平衡推导.png)

以向外为正方向，有：

重力：

<img src="https://www.zhihu.com/equation?tex=\mathrm{d}F_g = -G M(r)\frac{\mathrm{d}m}{r^2}=-G M(r)\frac{\rho \mathrm{d}A\mathrm{d}r}{r^2}
\tag{1}
" alt="\mathrm{d}F_g = -G M(r)\frac{\mathrm{d}m}{r^2}=-G M(r)\frac{\rho \mathrm{d}A\mathrm{d}r}{r^2}
\tag{1}
" class="ee_img tr_noresize" eeimg="1">
压力差为：

<img src="https://www.zhihu.com/equation?tex=\mathrm{d}F_P = F_{P,b}dA-F_{P,t}dA=-dPdA
\tag{2}
" alt="\mathrm{d}F_P = F_{P,b}dA-F_{P,t}dA=-dPdA
\tag{2}
" class="ee_img tr_noresize" eeimg="1">
由牛顿第二定律，有

<img src="https://www.zhihu.com/equation?tex=dm\frac{d^2r}{dt^2} = dF_g+dF_P
\tag{3}
" alt="dm\frac{d^2r}{dt^2} = dF_g+dF_P
\tag{3}
" class="ee_img tr_noresize" eeimg="1">
代入上述公式有：

<img src="https://www.zhihu.com/equation?tex=\rho\frac{d^2r}{dt^2}=-G\frac{M(r)\rho}{r^2}-\frac{dP}{dr}
\tag{4}
" alt="\rho\frac{d^2r}{dt^2}=-G\frac{M(r)\rho}{r^2}-\frac{dP}{dr}
\tag{4}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=M(r)" alt="M(r)" class="ee_img tr_noresize" eeimg="1"> 是距离恒星中心 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 以内球体的质量。这是由万有引力的性质所决定的。（回想性质：匀质球壳内部所受到的万有引力为0）

考虑**恒星是静态**的，有：

<img src="https://www.zhihu.com/equation?tex=\frac{dP}{dr}=-G\frac{M(r)\rho}{r^2}=-\rho g
\tag{5}
" alt="\frac{dP}{dr}=-G\frac{M(r)\rho}{r^2}=-\rho g
\tag{5}
" class="ee_img tr_noresize" eeimg="1">
其中的 <img src="https://www.zhihu.com/equation?tex=g" alt="g" class="ee_img tr_noresize" eeimg="1"> 是半径 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 处的本地引力加速度。

于是由上式，我们可以得出这样的结论：为了使恒星能够处于静态，需要压强梯度力与引力平衡，并且压强随着半径的增加而减少。

##### 2. 质量守恒公式

同样我们可以考察恒星质量随半径的变化关系：考虑距离恒星中心 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 处的球壳：

<img src="https://www.zhihu.com/equation?tex=dM_r=\rho (4\pi r^2dr)
\tag{6}
" alt="dM_r=\rho (4\pi r^2dr)
\tag{6}
" class="ee_img tr_noresize" eeimg="1">
可以得到**质量守恒公式**：

<img src="https://www.zhihu.com/equation?tex=\frac{dM_r}{dr} = 4\pi r^2 \rho
\tag{7}
" alt="\frac{dM_r}{dr} = 4\pi r^2 \rho
\tag{7}
" class="ee_img tr_noresize" eeimg="1">

### 二，状态方程 Equation of State


<img src="https://www.zhihu.com/equation?tex=PV=NkT=nRT
\tag{8}
" alt="PV=NkT=nRT
\tag{8}
" class="ee_img tr_noresize" eeimg="1">

其中， <img src="https://www.zhihu.com/equation?tex=k" alt="k" class="ee_img tr_noresize" eeimg="1"> 是玻尔兹曼常量， <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> 是普适气体常量，一个对应于微观态，一个对应于宏观态，有关系：

<img src="https://www.zhihu.com/equation?tex=R=\frac{Nk}{n}
\tag{9}
" alt="R=\frac{Nk}{n}
\tag{9}
" class="ee_img tr_noresize" eeimg="1">


##### 1. 压强积分的推导

（由于篇幅稍长，且markdown语句还不熟练，为节省时间，用手写推导。后面的笔记也可能采用该方式。）

![image-20240405103315403](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/压强积分的推导.png)

##### 2. 用平均分子量表示理想气体定律

![image-20240405103330925](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/平均分子量表示理想气体定律.png)

![image-20240405103435168](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/平均分子量的推导1.png)

![image-20240405103520532](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/平均分子量的推导2.png)

假设 <img src="https://www.zhihu.com/equation?tex=X=0.70,\ Y=0.28,\ Z=0.02" alt="X=0.70,\ Y=0.28,\ Z=0.02" class="ee_img tr_noresize" eeimg="1"> （这是比较年轻的恒星的典型成分），那么我们有 <img src="https://www.zhihu.com/equation?tex=\mu_n=1.30,\ \mu_i=0.62" alt="\mu_n=1.30,\ \mu_i=0.62" class="ee_img tr_noresize" eeimg="1"> 。

##### 3. 每个粒子的平均动能

根据**能量均分的原则**，每个粒子的平均动能为：

<img src="https://www.zhihu.com/equation?tex=\frac{1}{2}mv^2=\frac{3}{2}kT
\tag{34}
" alt="\frac{1}{2}mv^2=\frac{3}{2}kT
\tag{34}
" class="ee_img tr_noresize" eeimg="1">

##### 4. 辐射压的贡献

由于**光子具有动量** <img src="https://www.zhihu.com/equation?tex=p_\gamma=h\nu/c" alt="p_\gamma=h\nu/c" class="ee_img tr_noresize" eeimg="1"> ，所以在光子的吸收与反射中会向其他例子传递冲量。于是考虑**辐射压**，对（19）进行改写，有：

<img src="https://www.zhihu.com/equation?tex=P_{rad}=\frac{1}{3}\int_0^\infty h\nu n_\nu d\nu
\tag{35}
" alt="P_{rad}=\frac{1}{3}\int_0^\infty h\nu n_\nu d\nu
\tag{35}
" class="ee_img tr_noresize" eeimg="1">
可以类似得考虑 <img src="https://www.zhihu.com/equation?tex=n_\nu d\nu" alt="n_\nu d\nu" class="ee_img tr_noresize" eeimg="1"> 为频率位于 <img src="https://www.zhihu.com/equation?tex=\nu \sim \nu+d\nu" alt="\nu \sim \nu+d\nu" class="ee_img tr_noresize" eeimg="1"> 的**光子数密度**，而引入**能量密度** <img src="https://www.zhihu.com/equation?tex=u_\nu d\nu=h\nu n_\nu d\nu" alt="u_\nu d\nu=h\nu n_\nu d\nu" class="ee_img tr_noresize" eeimg="1"> ，有，

<img src="https://www.zhihu.com/equation?tex=P_{rad}=\frac{1}{3}\int_0^\infty u_\nu d\nu
\tag{36}
" alt="P_{rad}=\frac{1}{3}\int_0^\infty u_\nu d\nu
\tag{36}
" class="ee_img tr_noresize" eeimg="1">
结合**黑体辐射**中的**能量密度分布函数**，可以得出，

<img src="https://www.zhihu.com/equation?tex=P_{rad} = \frac{1}{3}\int_0^\infty aT^4
\tag{37}
" alt="P_{rad} = \frac{1}{3}\int_0^\infty aT^4
\tag{37}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=a" alt="a" class="ee_img tr_noresize" eeimg="1"> 为**辐射常数**。 <img src="https://www.zhihu.com/equation?tex=a=4\sigma/c" alt="a=4\sigma/c" class="ee_img tr_noresize" eeimg="1"> ，这里的 <img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1"> 是斯特藩-玻尔兹曼常数， <img src="https://www.zhihu.com/equation?tex=a=7.565767 \times 10^{-16} J\cdot m^{-3}\cdot K^{-4}" alt="a=7.565767 \times 10^{-16} J\cdot m^{-3}\cdot K^{-4}" class="ee_img tr_noresize" eeimg="1"> 。

于是总压强为：

<img src="https://www.zhihu.com/equation?tex=P_t=\frac{\rho k T}{\mu m_H}+\frac{1}{3}aT^4
\tag{38}
" alt="P_t=\frac{\rho k T}{\mu m_H}+\frac{1}{3}aT^4
\tag{38}
" class="ee_img tr_noresize" eeimg="1">
我们可以从上述的结果得到关于**恒星质量与光度关系**的解释：质量大的恒星引力越强，那么根据流体静力学平衡，所要求的内部压强也就越强；根据状态方程，压强越强压球内部温度越高，于是光度也就越高了。

### 三，恒星能源 Stellar Energy Source

恒星的能量输出率非常大，探究清楚恒星功能的机制对于研究恒星的结构有着重要的作用。天文学发展史上，有着各种不同对于恒星能源的解释。

##### 1. 引力和开尔文-亥姆霍兹时标 Kelvin-Helmholtz

恒星能量来源的可能之一是**引力势能**。

引力势能的表达式为：

<img src="https://www.zhihu.com/equation?tex=U=-G\frac{Mm}{r}
\tag{39}
" alt="U=-G\frac{Mm}{r}
\tag{39}
" class="ee_img tr_noresize" eeimg="1">
考虑引力收缩，如果 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 减小，那么引力势能会减小，那么引力势能就会转换为其他形式。**如果存在这样一种机制，使得恒星能够把引力势能转换为热能**，向外辐射的话。根据位力定理，处于平衡态粒子系统的总能量是系统势能的一半，因此恒星势能变化只有一半可以辐射出去，另一半则提供热能加热恒星。

考虑距离恒心中心 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 处的球壳，

<img src="https://www.zhihu.com/equation?tex=dm=4\pi r^2\rho dr
\tag{40}
" alt="dm=4\pi r^2\rho dr
\tag{40}
" class="ee_img tr_noresize" eeimg="1">
那么这个球壳的引力势能为。

<img src="https://www.zhihu.com/equation?tex=dU_g=-G\frac{M_r 4 \pi r^2 \rho}{r}dr
\tag{41}
" alt="dU_g=-G\frac{M_r 4 \pi r^2 \rho}{r}dr
\tag{41}
" class="ee_img tr_noresize" eeimg="1">
积分，得总引力势能，

<img src="https://www.zhihu.com/equation?tex=U_g=-4\pi G\int_0^R M_r \rho rdr
\tag{42}
" alt="U_g=-4\pi G\int_0^R M_r \rho rdr
\tag{42}
" class="ee_img tr_noresize" eeimg="1">
假设 <img src="https://www.zhihu.com/equation?tex=\rho" alt="\rho" class="ee_img tr_noresize" eeimg="1"> 是常数，代入平均密度进行估算，有，

<img src="https://www.zhihu.com/equation?tex=U_g \sim -\frac{16 \pi^2}{15} G \rho^2R^5 \sim -\frac{3}{5}\frac{GM^2}{R}
\tag{43}
" alt="U_g \sim -\frac{16 \pi^2}{15} G \rho^2R^5 \sim -\frac{3}{5}\frac{GM^2}{R}
\tag{43}
" class="ee_img tr_noresize" eeimg="1">
利用位力定律，有，

<img src="https://www.zhihu.com/equation?tex=E\sim-\frac{3}{10}\frac{GM^2}{R}
\tag{44}
" alt="E\sim-\frac{3}{10}\frac{GM^2}{R}
\tag{44}
" class="ee_img tr_noresize" eeimg="1">
考虑太阳的演化：假设太阳原本比现在大得多，那么**初始的引力势能可以忽略不计**，则演化到现在辐射出的能量为，

<img src="https://www.zhihu.com/equation?tex=\Delta E_g \sim -\frac{3}{10}\frac{GM_\odot^2}{R_\odot} \sim 1.1\times 10^{41}J
\tag{44}
" alt="\Delta E_g \sim -\frac{3}{10}\frac{GM_\odot^2}{R_\odot} \sim 1.1\times 10^{41}J
\tag{44}
" class="ee_img tr_noresize" eeimg="1">
**假设太阳的光度保持不变**，那么算出以这样的速率释放能量的时间大约是，

<img src="https://www.zhihu.com/equation?tex=t_{KH}=\frac{\Delta E_g}{L_\odot} \sim 10^7 yr
\tag{45}
" alt="t_{KH}=\frac{\Delta E_g}{L_\odot} \sim 10^7 yr
\tag{45}
" class="ee_img tr_noresize" eeimg="1">
此为**开尔文-亥姆霍兹时标**。

但我们有很多的证据表明太阳的寿命不可能这么短，例如月球表面岩石的年龄测定等等。

另外，如果考虑化学过程的供能机制，化学能提供的能量远不足以太阳辐射需要的能量，因此也可以排除。

##### 2. 核反应

1920年，卢瑟福等人测定了原子核的质量，于是爱丁顿受此启发，提出恒星的能量源自于将氢聚变为氦的核反应。

而后在1938年，贝特等人提出氢原子核聚变的质子质子链反应和碳氮氧循环；1957年，霍伊尔、帕比奇夫妇和福勒四人提出了元素合成理论，即 <img src="https://www.zhihu.com/equation?tex=\mathrm{B^2FH}" alt="\mathrm{B^2FH}" class="ee_img tr_noresize" eeimg="1"> 理论。

![image-20240405112447221](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/核反应的特征势能曲线.png)

上图中，Coulomb repulsion 指的是库伦排斥，Deuterium binding energy 指的是氘核结合能，Strong nuclear potential well 指的是强核势阱。

**带正电的原子核之间的库伦排斥导致势垒**，其与原子核之间的间距成反比，与电荷的乘积成正比。**原子核内部的核势阱是由强核力的吸引而产生的**。也就是说，只要核子之间能够克服库仑势垒，那么核反应就能比较容易地发生了。（想象两个粒子彼此靠近的过程，就是从上图的右侧向左侧移动的过程。要想发生核反应，就要越过或者穿过库仑势垒）

简单估算核反应需要的温度：令动能完全克服库伦势能，

<img src="https://www.zhihu.com/equation?tex=\frac{3}{2}kT=\frac{1}{4 \pi \varepsilon}\frac{Z_1Z_2e^2}{r}
\tag{46}
" alt="\frac{3}{2}kT=\frac{1}{4 \pi \varepsilon}\frac{Z_1Z_2e^2}{r}
\tag{46}
" class="ee_img tr_noresize" eeimg="1">
计算得 <img src="https://www.zhihu.com/equation?tex=T\sim 6\times 10^9 K" alt="T\sim 6\times 10^9 K" class="ee_img tr_noresize" eeimg="1"> 。但是太阳核心的温度只有 <img src="https://www.zhihu.com/equation?tex=10^7" alt="10^7" class="ee_img tr_noresize" eeimg="1"> 的数量级。

但是我们不必慌张，根据量子力学中的海森堡测不准原理（Heisenberg uncertainty principle），即是质子的动能不足以克服库仑势垒，它也有一定的概率可以穿过它，并且与另一个质子发生碰撞。

位置和动量的不确定关系：

<img src="https://www.zhihu.com/equation?tex=\Delta x \Delta p_x \geqslant \frac{\hbar}{2}
\tag{47}
" alt="\Delta x \Delta p_x \geqslant \frac{\hbar}{2}
\tag{47}
" class="ee_img tr_noresize" eeimg="1">
大质量粒子的波长为 <img src="https://www.zhihu.com/equation?tex=\lambda = h/p" alt="\lambda = h/p" class="ee_img tr_noresize" eeimg="1"> ，改写动能：

<img src="https://www.zhihu.com/equation?tex=\frac{1}{2}\mu_m v^2=\frac{p^2}{2\mu_m}
\tag{48}
" alt="\frac{1}{2}\mu_m v^2=\frac{p^2}{2\mu_m}
\tag{48}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=\mu_m" alt="\mu_m" class="ee_img tr_noresize" eeimg="1"> 是约化质量（两个原子核的折合质量）。假设两个质子最靠近的距离为 <img src="https://www.zhihu.com/equation?tex=\lambda" alt="\lambda" class="ee_img tr_noresize" eeimg="1"> ，那么有：

<img src="https://www.zhihu.com/equation?tex=\frac{1}{4 \pi \varepsilon}\frac{Z_1Z_2e^2}{r} = \frac{p^2}{2\mu_m}=\frac{(h/\lambda)^2}{2\mu_m}
\tag{49}
" alt="\frac{1}{4 \pi \varepsilon}\frac{Z_1Z_2e^2}{r} = \frac{p^2}{2\mu_m}=\frac{(h/\lambda)^2}{2\mu_m}
\tag{49}
" class="ee_img tr_noresize" eeimg="1">
于是有（代入 <img src="https://www.zhihu.com/equation?tex=\mu_m=m_p/2,\ Z_1=Z_2=1" alt="\mu_m=m_p/2,\ Z_1=Z_2=1" class="ee_img tr_noresize" eeimg="1"> ）：

<img src="https://www.zhihu.com/equation?tex=T=\frac{Z_1^2Z_2^2e^4\mu_m}{12\pi^2 \varepsilon^2 h^2k} \sim 10^7K
\tag{50}
" alt="T=\frac{Z_1^2Z_2^2e^4\mu_m}{12\pi^2 \varepsilon^2 h^2k} \sim 10^7K
\tag{50}
" class="ee_img tr_noresize" eeimg="1">

##### 3. 热核反应的伽莫夫窗口

核反应率，或在这里更详细地表述为带电粒子之间的反应速率取决于两个因素：**粒子的速度分布**和**穿越库仑势垒的概率/反应截面**。

![image-20240405133642014](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/伽莫夫窗口.png)

根据公式推导，**核反应发生的概率是碰撞动能的函数**。伽莫夫峰由**麦克斯韦-玻尔兹曼分布 <img src="https://www.zhihu.com/equation?tex=e^{-E/kT}" alt="e^{-E/kT}" class="ee_img tr_noresize" eeimg="1"> 的高能尾部**和**库仑势垒穿透项 <img src="https://www.zhihu.com/equation?tex=e^{-bE^{-1/2}}" alt="e^{-bE^{-1/2}}" class="ee_img tr_noresize" eeimg="1"> 的贡献**引起。如上图两条虚线所示，注意，这里为了使曲线的趋势走向更清晰，进行了缩放。

##### 4. 核合成和守恒原理

一种元素转换为另一种元素的过程被称为**核合成**。对于太阳这样的恒星，考虑氢的“燃烧”，这是基于四个氢原子核转换为氦核的假设。要使这一过程发生，必须由一连串的反应产生最终产物。实际上是在假定任何时刻只有两个原子核碰撞的情况下发生核反应，从而导出反应率公式的。

且链式核反应过程应当遵守一系列的**粒子守恒定律**，尤其是电荷，核子数和轻子数守恒。（轻子包括电子，正电子，中微子，反中微子等）

用 <img src="https://www.zhihu.com/equation?tex={}_Z^A\!X" alt="{}_Z^A\!X" class="ee_img tr_noresize" eeimg="1"> 表示原子核的符号，其中A是质量数，Z是质子数。

氢燃烧：

<img src="https://www.zhihu.com/equation?tex=\mathrm{4 {}^1H \rightarrow {}^4 He +2 e^+ +E +2 \nu_e}
\tag{51}
" alt="\mathrm{4 {}^1H \rightarrow {}^4 He +2 e^+ +E +2 \nu_e}
\tag{51}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=\mathrm{E=(4m_H-m_{He})c^2 \approx 4 \times 10^{-5} erg}" alt="\mathrm{E=(4m_H-m_{He})c^2 \approx 4 \times 10^{-5} erg}" class="ee_img tr_noresize" eeimg="1"> 。

##### 5. 质子-质子链 proton-proton chain

主要发生在 <img src="https://www.zhihu.com/equation?tex=M<1.1M_\odot" alt="M<1.1M_\odot" class="ee_img tr_noresize" eeimg="1"> 的恒星，分为ppI, ppII, ppIII三种。其中ppI最重要。

ppI chain：

![image-20240405140618705](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/ppI.png)

ppII chain：

![image-20240405140652888](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/ppII.png)

ppIII chain：

![image-20240405140715121](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/ppIII.png)

pp链的三个分支：

![image-20240405140753523](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/pp链的三个分支.png)

##### 6. 碳氮氧循环

主要发生在 <img src="https://www.zhihu.com/equation?tex=M>1.1M_\odot" alt="M>1.1M_\odot" class="ee_img tr_noresize" eeimg="1"> 的恒星。在CNO循环中，C、N、O分别被用作催化剂，在该过程中它们被消耗后再生。

第一分支：

![image-20240405141208993](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/第一分支.png)

第二分支：

![image-20240405141229782](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/第二分支.png)



质子-质子链与碳氮氧循环核反应率的比较：

![质子-质子链与碳氮氧循环核反应率的比较](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/质子-质子链与碳氮氧循环核反应率的比较.png)

上图可知，CNO循环比pp链具有更强的温度依赖性。这也与前面所限制的恒星质量的条件相一致。

##### 7. H燃烧的 <img src="https://www.zhihu.com/equation?tex=3\alpha" alt="3\alpha" class="ee_img tr_noresize" eeimg="1"> 过程

对于比H更重的元素：

![比H更重元素的燃烧](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/比H更重元素的燃烧.png)

##### 8. 核反应与恒星内部结构的变化

更重的元素燃烧要求更高的核心温度。热核反应导致恒星内部形成洋葱一样的结构。但这一结构中元素的组分当然取决于恒星质量。

比结合能是每个核子的结合能，即 <img src="https://www.zhihu.com/equation?tex=E_b/A" alt="E_b/A" class="ee_img tr_noresize" eeimg="1"> ：

<img src="https://www.zhihu.com/equation?tex=E_b=\Delta mc^2= [Zm_p+(A-Z)m_n-m_{nucleus}]c^2
" alt="E_b=\Delta mc^2= [Zm_p+(A-Z)m_n-m_{nucleus}]c^2
" class="ee_img tr_noresize" eeimg="1">
下图是比结合能随质量数的关系：

![比结合能与质量数的关系曲线.png](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/比结合能与质量数的关系曲线.png)

其中峰值对应的是 <img src="https://www.zhihu.com/equation?tex=\mathrm{{}_{26}^{52}Fe}" alt="\mathrm{{}_{26}^{52}Fe}" class="ee_img tr_noresize" eeimg="1"> ，是所有元素中最稳定的（这是核力与电磁力在特定原子核中的平衡结果）。

于是当恒星核心区形成铁之后，由于铁的聚变反应吸热而不是放热，核心的核反应就停止了。但并不是所有的恒星都能“存活”到形成铁核的阶段。

![image-20240405142925489](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章-恒星内部（一）/洋葱结构.png)

