# 第10章 恒星内部（二）

书接上回，我们已经得到了恒星内部流体静力学平衡的条件；以及通过改写理想气体状态方程，用平均分子量表示的压强；并且知道了恒星能量的来源。

现在我们已经把基本量 <img src="https://www.zhihu.com/equation?tex=P,\ M,\ L" alt="P,\ M,\ L" class="ee_img tr_noresize" eeimg="1"> 通过微分公式与独立变量 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 建立了关系，如下：

1. 流体静力学平衡的条件：


<img src="https://www.zhihu.com/equation?tex=\frac{dP}{dr} = -G\frac{M_r\rho}{r^2}=-\rho g
\tag{1}
" alt="\frac{dP}{dr} = -G\frac{M_r\rho}{r^2}=-\rho g
\tag{1}
" class="ee_img tr_noresize" eeimg="1">

2. 质量守恒公式：


<img src="https://www.zhihu.com/equation?tex=\frac{dM_r}{dr}=4\pi r^2\rho
\tag{2}
" alt="\frac{dM_r}{dr}=4\pi r^2\rho
\tag{2}
" class="ee_img tr_noresize" eeimg="1">

3. 光度梯度公式：


<img src="https://www.zhihu.com/equation?tex=\frac{dL_r}{dr}=4\pi r^2 \rho \epsilon
\tag{3}
" alt="\frac{dL_r}{dr}=4\pi r^2 \rho \epsilon
\tag{3}
" class="ee_img tr_noresize" eeimg="1">

其中 <img src="https://www.zhihu.com/equation?tex=\epsilon=\epsilon_{\text{nuclear}}+\epsilon_{\text{gravity}}" alt="\epsilon=\epsilon_{\text{nuclear}}+\epsilon_{\text{gravity}}" class="ee_img tr_noresize" eeimg="1"> ，是每千克每秒所有核反应和引力释放的总能量。

还需要把温度 <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> 与 <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 联系起来的关系式。这也就是要考虑能量从核反应区传输到表面的机制。

### 四，能量传输 Energy Transport

##### 1. 三种能量传输的机制

在恒星内部有三种能量传输机制。

**辐射 Radiation**：由核反应和引力产生的能量经由**光子**被携带到表面。
**辐射传热**是指恒星内部的冷物质通过吸收热区的光子而加热。如果能够维持**辐射平衡**，那么恒星内部的产生的能量将全部由辐射向外传递。

**对流 Convection**：气体在**冷热区域之间**的大规模的**循环流动**。
随着恒星内部的不透明度或产能率增大，辐射梯度值增大（马上会提到），辐射平衡是不稳定的，这时候在恒星内部产生对流。
其过程就是**热气体膨胀上升，冷却后下沉，形成物质流动的循环和热量的传递**。
因此对流不仅**传递能量**，还起到**混合物质**的作用。

**传导 Conduction**：通过粒子间的碰撞传输热量。但在大多数恒星的一生中，传导几乎不起作用，此处不作过多讨论。

太阳核心区产生的能量主要通过**辐射**与**对流**向外传递。

##### 2. 辐射温度梯度

辐射压强梯度由下面的公式给出，其中 <img src="https://www.zhihu.com/equation?tex=\bar{\kappa}" alt="\bar{\kappa}" class="ee_img tr_noresize" eeimg="1"> 表示平均不透明度（具体的内容会在第9章中给出，但目前还没有看到那里），

<img src="https://www.zhihu.com/equation?tex=\frac{dP_{rad}}{dr}= -\frac{\bar{\kappa}\rho}{c}F_{rad}
\tag{4}
" alt="\frac{dP_{rad}}{dr}= -\frac{\bar{\kappa}\rho}{c}F_{rad}
\tag{4}
" class="ee_img tr_noresize" eeimg="1">
另外第10章笔记（一）中，有，

<img src="https://www.zhihu.com/equation?tex=\frac{dP_{rad}}{dr}=\frac{4}{3}aT^3\frac{dT}{dr}
\tag{5}
" alt="\frac{dP_{rad}}{dr}=\frac{4}{3}aT^3\frac{dT}{dr}
\tag{5}
" class="ee_img tr_noresize" eeimg="1">
令两式相等，并且用光度表示辐射流量 <img src="https://www.zhihu.com/equation?tex=F_{rad}=L_r/4\pi r^2" alt="F_{rad}=L_r/4\pi r^2" class="ee_img tr_noresize" eeimg="1"> ，有，

<img src="https://www.zhihu.com/equation?tex=\frac{dT}{dr}=-\frac{3}{4ac}\frac{\bar{\kappa}\rho}{T^3}\frac{L_r}{4\pi r^2}
\tag{6}
" alt="\frac{dT}{dr}=-\frac{3}{4ac}\frac{\bar{\kappa}\rho}{T^3}\frac{L_r}{4\pi r^2}
\tag{6}
" class="ee_img tr_noresize" eeimg="1">

##### 3. 压强标高

如果温度梯度变得太陡，不足以达到辐射平衡，那么**对流就开始在能量传输中起作用**。对流的特征尺度通常以压强标高来表示，它常常与恒星的大小相当。由于目前还未学习流体力学，故此处仅仅摘取了书上的简单结论（在此后会更新补充这一部分的内容）：

压强标高定义为，

<img src="https://www.zhihu.com/equation?tex=\frac{1}{H_P} \equiv -\frac{1}{P}\frac{dP}{dr}
\tag{7}
" alt="\frac{1}{H_P} \equiv -\frac{1}{P}\frac{dP}{dr}
\tag{7}
" class="ee_img tr_noresize" eeimg="1">
假设 <img src="https://www.zhihu.com/equation?tex=H_P" alt="H_P" class="ee_img tr_noresize" eeimg="1"> 为常数，可以解出压强随半径的变化，

<img src="https://www.zhihu.com/equation?tex=P=P_0 e^{-r/H_P}
\tag{8}
" alt="P=P_0 e^{-r/H_P}
\tag{8}
" class="ee_img tr_noresize" eeimg="1">
若考虑流体静力学平衡得到的压强随半径的变化关系，可以得到，

<img src="https://www.zhihu.com/equation?tex=H_P=\frac{P}{\rho g}
\tag{9}
" alt="H_P=\frac{P}{\rho g}
\tag{9}
" class="ee_img tr_noresize" eeimg="1">

##### 4. 绝热温度梯度

考虑热对流气泡上升并且**绝热膨胀**的情况，意味着气泡不与其周围环境进行热交换。

根据热力学的知识，绝热膨胀，有，

<img src="https://www.zhihu.com/equation?tex=PV^\gamma=K
\tag{10}
" alt="PV^\gamma=K
\tag{10}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> 为常数。考虑 <img src="https://www.zhihu.com/equation?tex=V\equiv 1/\rho" alt="V\equiv 1/\rho" class="ee_img tr_noresize" eeimg="1"> 是比体积，有，

<img src="https://www.zhihu.com/equation?tex=P=K\rho^\gamma
\tag{11}
" alt="P=K\rho^\gamma
\tag{11}
" class="ee_img tr_noresize" eeimg="1">
对（11）取微分有，

<img src="https://www.zhihu.com/equation?tex=\frac{dP}{dr}=\gamma\frac{P}{\rho}\frac{d\rho}{dr}
\tag{12}
" alt="\frac{dP}{dr}=\gamma\frac{P}{\rho}\frac{d\rho}{dr}
\tag{12}
" class="ee_img tr_noresize" eeimg="1">
由理想气体定律式 <img src="https://www.zhihu.com/equation?tex=P_g=\frac{\rho k T}{\mu m_H}" alt="P_g=\frac{\rho k T}{\mu m_H}" class="ee_img tr_noresize" eeimg="1"> ，微分有，

<img src="https://www.zhihu.com/equation?tex=\frac{dP}{dr}=-\frac{P}{\mu}\frac{d\mu}{dr}+\frac{P}{\rho}\frac{d\rho}{dr}+\frac{P}{T}\frac{dT}{dr}
\tag{13}
" alt="\frac{dP}{dr}=-\frac{P}{\mu}\frac{d\mu}{dr}+\frac{P}{\rho}\frac{d\rho}{dr}+\frac{P}{T}\frac{dT}{dr}
\tag{13}
" class="ee_img tr_noresize" eeimg="1">
联立（12）（13），可以得到

<img src="https://www.zhihu.com/equation?tex=\frac{dT}{dr}|_{ad}=-(1-\frac{1}{\gamma})\frac{\mu m_H}{k}\frac{GM_r}{r^2}
\tag{14}
" alt="\frac{dT}{dr}|_{ad}=-(1-\frac{1}{\gamma})\frac{\mu m_H}{k}\frac{GM_r}{r^2}
\tag{14}
" class="ee_img tr_noresize" eeimg="1">
其中

<img src="https://www.zhihu.com/equation?tex=\nabla = \frac{d\ln T}{d\ln P}=\nabla_{ad}=1-\frac{1}{\gamma}
\tag{15}
" alt="\nabla = \frac{d\ln T}{d\ln P}=\nabla_{ad}=1-\frac{1}{\gamma}
\tag{15}
" class="ee_img tr_noresize" eeimg="1">
当 <img src="https://www.zhihu.com/equation?tex=\nabla<\nabla_{ad}" alt="\nabla<\nabla_{ad}" class="ee_img tr_noresize" eeimg="1"> 时，为辐射区；当 <img src="https://www.zhihu.com/equation?tex=\nabla\geqslant\nabla_{ad}" alt="\nabla\geqslant\nabla_{ad}" class="ee_img tr_noresize" eeimg="1"> 时，为对流区。

![image-20240405203350321](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/温度梯度与半径关系图.png)

如上图所示，虚线为绝热膨胀情况下的温度梯度，即达到该值后，能量运输的方式以对流。

##### 5. 不同质量主序星的内部结构

对于较大质量的主序星（ <img src="https://www.zhihu.com/equation?tex=M>1.5-2M_\odot" alt="M>1.5-2M_\odot" class="ee_img tr_noresize" eeimg="1"> ），有

![image-20240405203651001](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/较大质量.png)

对于较小质量的主序星（ <img src="https://www.zhihu.com/equation?tex=0.8M_\odot<M<1.5-2M_\odot" alt="0.8M_\odot<M<1.5-2M_\odot" class="ee_img tr_noresize" eeimg="1"> ），例如太阳，有

![image-20240405203825060](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/较小质量.png)

对于极小质量的主序星（ <img src="https://www.zhihu.com/equation?tex=0.1M_\odot<M<0.8M_\odot" alt="0.1M_\odot<M<0.8M_\odot" class="ee_img tr_noresize" eeimg="1"> ），有

![image-20240405203935007](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/极小质量的主序星.png)

### 五，恒星模型建构

##### 1. 恒星结构公式综述

此处，我们总结在之前的讨论中得到的恒星结构公式：

1. 流体静力学平衡的条件：


<img src="https://www.zhihu.com/equation?tex=\frac{dP}{dr} = -G\frac{M_r\rho}{r^2}=-\rho g
\tag{16}
" alt="\frac{dP}{dr} = -G\frac{M_r\rho}{r^2}=-\rho g
\tag{16}
" class="ee_img tr_noresize" eeimg="1">

2. 质量守恒公式：


<img src="https://www.zhihu.com/equation?tex=\frac{dM_r}{dr}=4\pi r^2\rho
\tag{17}
" alt="\frac{dM_r}{dr}=4\pi r^2\rho
\tag{17}
" class="ee_img tr_noresize" eeimg="1">

3. 光度梯度公式：


<img src="https://www.zhihu.com/equation?tex=\frac{dL_r}{dr}=4\pi r^2 \rho \epsilon
\tag{18}
" alt="\frac{dL_r}{dr}=4\pi r^2 \rho \epsilon
\tag{18}
" class="ee_img tr_noresize" eeimg="1">

4. 温度梯度公式（辐射）：


<img src="https://www.zhihu.com/equation?tex=\frac{dT}{dr}=-\frac{3}{4ac}\frac{\kappa\rho}{T^3}\frac{L_r}{4\pi r^2}
\tag{19}
" alt="\frac{dT}{dr}=-\frac{3}{4ac}\frac{\kappa\rho}{T^3}\frac{L_r}{4\pi r^2}
\tag{19}
" class="ee_img tr_noresize" eeimg="1">

5. 温度梯度公式（绝热对流）：


<img src="https://www.zhihu.com/equation?tex=\frac{dT}{dr}=-(1-\frac{1}{\gamma})\frac{\mu m_H}{k}\frac{GM_r}{r^2}
\tag{20}
" alt="\frac{dT}{dr}=-(1-\frac{1}{\gamma})\frac{\mu m_H}{k}\frac{GM_r}{r^2}
\tag{20}
" class="ee_img tr_noresize" eeimg="1">

其中（20）适用于

<img src="https://www.zhihu.com/equation?tex=\frac{d \ln P}{d \ln T}<\frac{\gamma}{1-\gamma}
\tag{21}
" alt="\frac{d \ln P}{d \ln T}<\frac{\gamma}{1-\gamma}
\tag{21}
" class="ee_img tr_noresize" eeimg="1">
下面讨论恒星的产能率 <img src="https://www.zhihu.com/equation?tex=\epsilon" alt="\epsilon" class="ee_img tr_noresize" eeimg="1"> ，对于**静态**的恒星，有 <img src="https://www.zhihu.com/equation?tex=\epsilon=\epsilon_{nuclear}" alt="\epsilon=\epsilon_{nuclear}" class="ee_img tr_noresize" eeimg="1"> ；而对于**随时间演化**的恒星，应该考虑与时间相关系的引力项，有 <img src="https://www.zhihu.com/equation?tex=\epsilon^2=\epsilon_{nuclear}^2+\epsilon_{gravity}^2" alt="\epsilon^2=\epsilon_{nuclear}^2+\epsilon_{gravity}^2" class="ee_img tr_noresize" eeimg="1"> 。

根据**位力定理**，**损失的引力势能的一半要转换为热量**，于是有，

<img src="https://www.zhihu.com/equation?tex=\epsilon_{gravity}=-\frac{dQ}{dt}
\tag{22}
" alt="\epsilon_{gravity}=-\frac{dQ}{dt}
\tag{22}
" class="ee_img tr_noresize" eeimg="1">
这里的负号表示从物质中释放热量（因为一般规定 <img src="https://www.zhihu.com/equation?tex=dQ" alt="dQ" class="ee_img tr_noresize" eeimg="1"> 表示吸热）。

##### 2. 熵的角度

我们知道熵的定义为，

<img src="https://www.zhihu.com/equation?tex=dS \equiv \frac{dQ}{T}
\tag{23}
" alt="dS \equiv \frac{dQ}{T}
\tag{23}
" class="ee_img tr_noresize" eeimg="1">
那么代入（22），发现产能率是由于物质熵的变化导致的：

<img src="https://www.zhihu.com/equation?tex=\epsilon_{gravity}=-T\frac{dS}{dt}
\tag{24}
" alt="\epsilon_{gravity}=-T\frac{dS}{dt}
\tag{24}
" class="ee_img tr_noresize" eeimg="1">
简单分析，当恒星坍缩时，熵会减小，但是（24）式子有一个负号，于是产能率为正，这与事实相符。

##### 3. 本构关系

要想利用恒星结构公式描述恒星，还需要构成恒星的物质的物理性质的信息，即**关于物质状态的公式**，称为**本构关系**。根据物质的基本特性：密度、温度、成分，我们需要**压强**、**不透明度**和**产能率**之间的关系：

![image-20240405213956602](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/本构关系.png)

##### 4. 边界条件

恒星结构公式以及本构关系的实际解，需要适当的**边界条件**，以**明确数学公式的物理限制**。

恒星中心边界条件：

![image-20240405214226081](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/中心边界条件.png)

恒星表面边界条件：

![image-20240405214253991](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/恒星表面边界条件.png)

##### 5. 沃格特-罗素定理 Vogt-Russell

给定基本的恒星结构公式、本构关系和边界条件，我们现在可以对特定的恒星类型讲行建模。

根据之前的讨论，给定半径处的**压强梯度**取决于**内部质量和密度**；**辐射温度梯度**取决于**局部温度、密度、不透明度和内部光度**；**光度梯度**是**密度和产能率**的函数。**压强、不透明度和产能率**相应地又明确地取决于该位置处的**密度、温度和成分**。

如果在恒星表面处的内部质量(即整个恒星质量)是给定的，连同成分、表面半径和光度，以及表面边界条件的应用，允许确定在恒星表面之下**无限小距离dr处**的压强、内部质量、温度以及内部光度D。继续对恒星结构公式进行**数值积分**直到恒星的中心，必定导致与中心边界一致的结果。

**这其实与牛顿力学或者说经典力学的核心思路是一致的**：给定质点的初始位置和初始速度，以及质点的受力情况（加速度），便可以得到质点在任一时刻的位置和速度。

**由于各种梯度值与恒星成分直接相关，在选择了质量和成分之后，不可能指定表面半径和光度的任何任意组合**。这组限制称为**沃格特罗素定理**：

**一颗恒星的质量和成分结构唯一地决定了它的半径、光度和内部结构，以及随后的演化。**

##### 6. 恒星结构公式的数值模拟

除了多方球模型（下面会提到）以外，几乎不能对恒星结构公式作出解析解，但是可以采用**数值模拟**的方式求解。

与**沃格特-罗素定理**中讨论的情形一样，我们可以对无限小的变化作近似，即用差分公式来近似微分公式。例如， <img src="https://www.zhihu.com/equation?tex=\Delta P/\Delta r \rightarrow dP/dr" alt="\Delta P/\Delta r \rightarrow dP/dr" class="ee_img tr_noresize" eeimg="1"> 。限制增量为 <img src="https://www.zhihu.com/equation?tex=\delta r" alt="\delta r" class="ee_img tr_noresize" eeimg="1"> ，有

<img src="https://www.zhihu.com/equation?tex=P_{i+1} = P_i+\frac{\Delta P}{\Delta r}\delta r
\tag{25}
" alt="P_{i+1} = P_i+\frac{\Delta P}{\Delta r}\delta r
\tag{25}
" class="ee_img tr_noresize" eeimg="1">
![image-20240405215740106](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/数值恒星模拟中的分区.png)

通常情况下，数值积分是从表面到中心，以及中心到表面，同时在两个方向上进行的。

##### 7. 多方模型与莱恩-埃姆登公式 Lane-Emden

正如前面所说，通常不可能解析地求解恒星结构公式组及其相关的本构关系，我们必须使用数值解来构建恒星模型。但在非常特殊的和限定的情况下，有可能得到解析解。

霍默·莱恩与罗伯特·埃姆登为描述解析恒星模型作出了巨大贡献，此著名公式就称为**莱恩-埃姆登公式**。

我们再次分析（16）-（20）这一组恒星结构公式，不难发现，如果压强和密度之间仅仅存在一种简单的关系，那么（16）（17）两个公式可以在不参考（18）（19）（20）三个公式的情况下同时求解。这样的模型称为多方球，满足

<img src="https://www.zhihu.com/equation?tex=P=K\rho^{\gamma}
\tag{26}
" alt="P=K\rho^{\gamma}
\tag{26}
" class="ee_img tr_noresize" eeimg="1">
下面是莱恩-埃姆登公式的推导过程：

![image-20240406181217493](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/多方模型.png)

莱恩-埃姆登公式只有三个解析解，即 <img src="https://www.zhihu.com/equation?tex=n=0,1,5" alt="n=0,1,5" class="ee_img tr_noresize" eeimg="1"> ：

<img src="https://www.zhihu.com/equation?tex=D_0(\xi)=1-\frac{\xi^2}{6}, \quad \text{when }\xi_1=\sqrt{6} \\
D_1(\xi)=\frac{\sin\xi}{\xi}, \quad \text{when }\xi_1=\pi \\
D_5(\xi)=[1+\xi^2/3]^{-1/2}, \quad \text{when }\xi_1\rightarrow \infty
\tag{27}
" alt="D_0(\xi)=1-\frac{\xi^2}{6}, \quad \text{when }\xi_1=\sqrt{6} \\
D_1(\xi)=\frac{\sin\xi}{\xi}, \quad \text{when }\xi_1=\pi \\
D_5(\xi)=[1+\xi^2/3]^{-1/2}, \quad \text{when }\xi_1\rightarrow \infty
\tag{27}
" class="ee_img tr_noresize" eeimg="1">


![image-20240406181055167](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/解析解.png)

白矮星等某些极度致密的恒星可以用指数为1.5的多方球来描述，与辐射平衡的恒星相关联的爱丁顿标准模型的指数为3。但这些均无法做出解析解。

### 六，主序 the Main Sequence

根据对恒星光谱的分析，我们知道绝大多数的恒星大气主要由氢组成，金属的占比非常小（这里的金属指的是比氦重的元素）。

在最初的核球中，首先进行的核反应应当是氢燃烧转化为氦的反应。随着氢的燃烧，恒星的元素组成发生变化，会进而影响恒星的内部成分和结构。

根据上一小节提到的**沃格特-罗素定理**，如果恒星处于流体静力学平衡和热平衡，而且它的能量来自内部的核反应，那么它们的结构和演化就完全唯一地由**初始质量**和**化学丰度**所决定。

绝大多数的恒星具有相似的成分，这使得我们可以考虑其结构随着质量的变化而平稳变化的过程。根据之前的讨论，随着质量的增加，恒星中心的温度和压强增加。对于小质量的恒星，pp链占主导；对于大质量的恒星，CNO循环占主导。这与**核反应方式对温度依赖性的差异有关**。质量过小的恒星的核反应将无法抵抗引力收缩的作用；质量过大的恒星中心会受到热振荡的影响。

##### 1. 爱丁顿光度极限

回忆在（一）中导出的总压强的表示式，

<img src="https://www.zhihu.com/equation?tex=P_t=\frac{\rho kT}{\mu m_H}+\frac{1}{3}aT^4
\tag{}
" alt="P_t=\frac{\rho kT}{\mu m_H}+\frac{1}{3}aT^4
\tag{}
" class="ee_img tr_noresize" eeimg="1">
当温度足够高，而气体密度足够低的时候，**辐射压将占主导**，这种情况容易发生在大质量恒星的外层。恒星接近表面的压强梯度如下给出，

<img src="https://www.zhihu.com/equation?tex=\frac{dP}{dr}\simeq -\frac{\bar{\kappa}\rho}{c}\frac{L}{4\pi r^2}
\tag{}
" alt="\frac{dP}{dr}\simeq -\frac{\bar{\kappa}\rho}{c}\frac{L}{4\pi r^2}
\tag{}
" class="ee_img tr_noresize" eeimg="1">
而根据流体静力学平衡的条件，有，

<img src="https://www.zhihu.com/equation?tex=\frac{dP}{dr}=-G\frac{M\rho}{r^2}
\tag{}
" alt="\frac{dP}{dr}=-G\frac{M\rho}{r^2}
\tag{}
" class="ee_img tr_noresize" eeimg="1">
联立上面两个式子，有，

<img src="https://www.zhihu.com/equation?tex=L_{Ed}=\frac{4\pi Gc}{\bar{\kappa}}M
\tag{}
" alt="L_{Ed}=\frac{4\pi Gc}{\bar{\kappa}}M
\tag{}
" class="ee_img tr_noresize" eeimg="1">
 <img src="https://www.zhihu.com/equation?tex=L_{Ed}" alt="L_{Ed}" class="ee_img tr_noresize" eeimg="1"> 为恒星的爱丁顿极限，即一颗恒星所能拥有且仍能保持流体静力学平衡的最大辐射光度。

##### 2. 主序恒星参数随质量的变化

计算不同质量恒星的氢燃烧模型，可以在理论的赫罗图上定位这些恒星的位置，有下面的结果：

![image-20240405210943437](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第10章 恒星内部（二）/恒星模型与赫罗图.png)

由图，我们发现这与赫罗图上的主序吻合得很好。

进一步研究上图，不难发现，恒星质量的跨度大约为3个数量级，但是光度的跨度竟然达到了9个数量级。由于大质量恒星的高能量消耗速率，**主序星的寿命随着光度的增加而减少**。

有效温度 <img src="https://www.zhihu.com/equation?tex=T_e" alt="T_e" class="ee_img tr_noresize" eeimg="1"> 的变化就小很多了，仅仅只有几十倍的跨度。但是这样的温度范围的跨度，已经足够含括许多分子的解离能与元素的电离能，因此**不同质量恒星的光谱差异是很大的**。

不同质量的主序星的内部结构也不同，主要体现在**对流区的位置**。这与第四小节的第5部分给出的结构一致。

详细的恒星演化的过程，将在后续几章中讨论。

***由于笨人水平和时间尚不支撑完全读懂并推导书中的公式，因此还需要再未来的学习过程中，及时更新改进笔记，取得进步。***