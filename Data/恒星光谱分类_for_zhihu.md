# 恒星光谱分类

### 一，谱线的形成

##### 1，恒星的光谱型

Oh Be A Fine Girl/Guy, Kiss Me! 一代又一代的天文学专业的同学通过这个口诀来记忆光谱类型。最早是在十九世纪九十年代，Edward C. Pickering 和 Williamina P. Fleming 发展了光谱分类学，根据**氢吸收线的强度**，从A开始表示最宽的谱线。之后经过 Antonia Maury 和 Annie Jump Cannon 的改进，将O，B型放在了A型前面，并添加了数字分支，最终形成了温度序列：OBAFGKM。

**光谱类型**：**O,B,A,F,G,K,M**

这一序列中，靠近O的是**早型**恒星，靠近M的是**晚型**恒星。在同一个字母名下的恒星，又通过数字进行分类。例如K0型星称为**早期**K型星，B9型星称为**晚期**B型星。

Cannon最后将研究结果集结到**亨利·德雷伯星表**中。（1872年，亨利·德雷伯拍摄了第一张恒星光谱）

当原子**吸收了光子**，而光子的能量恰好可以**使电子从能量较低的轨道向上跃迁到能量较高的轨道**时，就会产生**吸收谱线**。
而当**电子从能量较高的轨道向较低的轨道向下跃迁**时，单个光子带走了电子失去的能量，就会产生**发射谱线**。

具有**不同温度**的恒星的光谱之间的差异可能是由于电子在这些恒星的大气中占据了**不同的原子轨道**，即处于不同的能级。
原子的电离态在原子符号后用罗马字符表示。例如 <img src="https://www.zhihu.com/equation?tex=\mathrm{H \:I}" alt="\mathrm{H \:I}" class="ee_img tr_noresize" eeimg="1"> , <img src="https://www.zhihu.com/equation?tex=\mathrm{He \:I}" alt="\mathrm{He \:I}" class="ee_img tr_noresize" eeimg="1"> 表示中性的氢和氦； <img src="https://www.zhihu.com/equation?tex=\mathrm{He\:II}" alt="\mathrm{He\:II}" class="ee_img tr_noresize" eeimg="1"> 表示单次电离的氦。以此类推。

![image-20240320195908832](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/哈佛光谱分类.png)

其中L型表示很冷的暗红色恒星；T型表示最冷的发红外线的褐矮星。

![image-20240320200356067](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/O9~F5.png)

![image-20240320200428295](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/F5~M5.png)

上面两张图是各种光谱类型的样品图片。我们会发现，图中的氢谱线（例如 <img src="https://www.zhihu.com/equation?tex=\mathrm{H_\gamma}:4344\AA,\mathrm{H_\delta}:4101\AA" alt="\mathrm{H_\gamma}:4344\AA,\mathrm{H_\delta}:4101\AA" class="ee_img tr_noresize" eeimg="1"> ）从O9到A0不断增加，又从A0到F5不断减少，最后到晚期的K型星几乎消失。而氦谱线则是在早型星中能观测到，较冷的恒星就观测不到了。

再看不同类型星的谱线波长与流量的关系图：

![image-20240320200956783](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/O5~F0.png)

![image-20240320201027748](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/F6~K5.png)

很容易从图中得出黑体辐射谱线的基本特点——当温度降低时，峰值对应的波长向长波移动。

##### 2，麦克斯韦—玻尔兹曼速度分布

为了进一步去探讨这些光谱型分类其中的物理机制，我们需要先回答：**在怎样的轨道上最容易发现电子**？**处在不同电离态的原子的相对数目是多少**？为此我们需要从统计的角度研究这个问题。

尽管我们不能计算出任意单个粒子的运动行为，但是可以从统计的角度，给出气体作为一个整体具有的某些明确的性质，例如温度，体积，密度等等。

对于处于热平衡的气体，可以用麦克斯韦—**玻尔兹曼速度分布函数**描述给定速度范围内粒子的比例。单位体积内，速度在 <img src="https://www.zhihu.com/equation?tex=v \sim v+dv" alt="v \sim v+dv" class="ee_img tr_noresize" eeimg="1"> 的气体粒子数目：

<img src="https://www.zhihu.com/equation?tex=n_vdv=n(\frac{m}{2\pi kT})^{3/2}e^{-mv^2/(2kT)}4\pi v^2 dv
\tag{1}
" alt="n_vdv=n(\frac{m}{2\pi kT})^{3/2}e^{-mv^2/(2kT)}4\pi v^2 dv
\tag{1}
" class="ee_img tr_noresize" eeimg="1">
 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 是总的数密度，即单位体积内的粒子数。 <img src="https://www.zhihu.com/equation?tex=n_v=\partial n /\partial v" alt="n_v=\partial n /\partial v" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=k" alt="k" class="ee_img tr_noresize" eeimg="1"> 是玻尔兹曼常量。分布函数的指数是气体粒子的动能（ <img src="https://www.zhihu.com/equation?tex=\frac{1}{2}mv^2" alt="\frac{1}{2}mv^2" class="ee_img tr_noresize" eeimg="1"> ）与特征热能（ <img src="https://www.zhihu.com/equation?tex=kT" alt="kT" class="ee_img tr_noresize" eeimg="1"> ）的比值。

不难验证，当动能与内能相等的时候，分布达到峰值，这时候的速度称为**最概然速度**：

<img src="https://www.zhihu.com/equation?tex=v_{mp}=\sqrt{\frac{2kT}{m}}
\tag{2}
" alt="v_{mp}=\sqrt{\frac{2kT}{m}}
\tag{2}
" class="ee_img tr_noresize" eeimg="1">
对速度的平方求平均值后，再取根号，得到**均方根速度**：

<img src="https://www.zhihu.com/equation?tex=v_{rms}=\sqrt{\frac{3kT}{m}}
\tag{3}
" alt="v_{rms}=\sqrt{\frac{3kT}{m}}
\tag{3}
" class="ee_img tr_noresize" eeimg="1">

##### 3，玻尔兹曼公式

以 <img src="https://www.zhihu.com/equation?tex=s_a" alt="s_a" class="ee_img tr_noresize" eeimg="1"> 代表一组特定的量子数，能态为 <img src="https://www.zhihu.com/equation?tex=E_a" alt="E_a" class="ee_img tr_noresize" eeimg="1"> 。例如 <img src="https://www.zhihu.com/equation?tex=s_a=\{n=1,l=0,m_l=0,m_s=+1/2\}" alt="s_a=\{n=1,l=0,m_l=0,m_s=+1/2\}" class="ee_img tr_noresize" eeimg="1"> ，以此表示基态能量 <img src="https://www.zhihu.com/equation?tex=E_a=-13.6eV" alt="E_a=-13.6eV" class="ee_img tr_noresize" eeimg="1"> 的量子数。

于是系统处于状态 <img src="https://www.zhihu.com/equation?tex=s_a,s_b" alt="s_a,s_b" class="ee_img tr_noresize" eeimg="1"> 的能量可以由下式给出：

<img src="https://www.zhihu.com/equation?tex=\frac{P(s_b)}{P(s_a)}=\frac{e^{-E_b/(kT)}}{e^{-E_a/(kT)}}=e^{-(E_b-E_a)/(kT)}
\tag{4}
" alt="\frac{P(s_b)}{P(s_a)}=\frac{e^{-E_b/(kT)}}{e^{-E_a/(kT)}}=e^{-(E_b-E_a)/(kT)}
\tag{4}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=e^{-E/(kT)}" alt="e^{-E/(kT)}" class="ee_img tr_noresize" eeimg="1"> 称为**玻尔兹曼因子**。得到的结果是符合推理的。例如令 <img src="https://www.zhihu.com/equation?tex=E_b>E_a" alt="E_b>E_a" class="ee_img tr_noresize" eeimg="1"> ，当温度足够高的时候， <img src="https://www.zhihu.com/equation?tex=P(s_b)/P(s_a)\rightarrow 1" alt="P(s_b)/P(s_a)\rightarrow 1" class="ee_img tr_noresize" eeimg="1"> ，这与具有无限多热能的情况下，原子应该可以等概率地进入各个能级的预期相符。

现在考虑能级间的**简并**，如果 <img src="https://www.zhihu.com/equation?tex=s_a,s_b" alt="s_a,s_b" class="ee_img tr_noresize" eeimg="1"> 是简并的，意味着有 <img src="https://www.zhihu.com/equation?tex=s_a \neq s_b" alt="s_a \neq s_b" class="ee_img tr_noresize" eeimg="1"> ，但是 <img src="https://www.zhihu.com/equation?tex=E_a =E_b" alt="E_a =E_b" class="ee_img tr_noresize" eeimg="1"> 。我们引入 <img src="https://www.zhihu.com/equation?tex=g" alt="g" class="ee_img tr_noresize" eeimg="1"> 因子，作为能级的**简并度**，也就是能级的**统计权重**，例如 <img src="https://www.zhihu.com/equation?tex=g_a" alt="g_a" class="ee_img tr_noresize" eeimg="1"> 表示能量为 <img src="https://www.zhihu.com/equation?tex=E_a" alt="E_a" class="ee_img tr_noresize" eeimg="1"> 的状态的总数。那么（4）可以改写为：

<img src="https://www.zhihu.com/equation?tex=\frac{P(s_b)}{P(s_a)}=\frac{g_be^{-E_b/(kT)}}{g_ae^{-E_a/(kT)}}=\frac{g_b}{g_a}e^{-(E_b-E_a)/(kT)}
\tag{5}
" alt="\frac{P(s_b)}{P(s_a)}=\frac{g_be^{-E_b/(kT)}}{g_ae^{-E_a/(kT)}}=\frac{g_b}{g_a}e^{-(E_b-E_a)/(kT)}
\tag{5}
" class="ee_img tr_noresize" eeimg="1">
恒星大气中的原子数目是庞大的，这时候可以将概率之比近似为原子数目之比：

<img src="https://www.zhihu.com/equation?tex=\frac{N_b}{N_a}=\frac{g_be^{-E_b/(kT)}}{g_ae^{-E_a/(kT)}}=\frac{g_b}{g_a}e^{-(E_b-E_a)/(kT)}
\tag{6}
" alt="\frac{N_b}{N_a}=\frac{g_be^{-E_b/(kT)}}{g_ae^{-E_a/(kT)}}=\frac{g_b}{g_a}e^{-(E_b-E_a)/(kT)}
\tag{6}
" class="ee_img tr_noresize" eeimg="1">
这样我们其实回答了在某一给定的温度下，“**在怎样的轨道上最容易发现电子**？”的问题。

##### 4，萨哈公式

设 <img src="https://www.zhihu.com/equation?tex=\mathcal{X_i}" alt="\mathcal{X_i}" class="ee_img tr_noresize" eeimg="1"> 为从基态的原子（或离子）中移除一个电子所需的电离能，从而将其从电离态 <img src="https://www.zhihu.com/equation?tex=i" alt="i" class="ee_img tr_noresize" eeimg="1"> 变成电离态 <img src="https://www.zhihu.com/equation?tex=i+1" alt="i+1" class="ee_img tr_noresize" eeimg="1"> 。例如从 <img src="https://www.zhihu.com/equation?tex=\mathrm{H \: I}" alt="\mathrm{H \: I}" class="ee_img tr_noresize" eeimg="1"> 到 <img src="https://www.zhihu.com/equation?tex=\mathrm{H \:II}" alt="\mathrm{H \:II}" class="ee_img tr_noresize" eeimg="1"> 所需的能量就是 <img src="https://www.zhihu.com/equation?tex=\mathcal{X_i}=13.6eV" alt="\mathcal{X_i}=13.6eV" class="ee_img tr_noresize" eeimg="1"> 。但是初始或者最终的离子可能并不处于基态，于是我们需要考虑电子在不同轨道上的分布。

引入**配分函数** <img src="https://www.zhihu.com/equation?tex=Z" alt="Z" class="ee_img tr_noresize" eeimg="1"> ，即原子以相同能量排列其电子方式数目的加权之和：

<img src="https://www.zhihu.com/equation?tex=Z=\sum_{j=1}^\infty g_je^{-(E_j-E_1)/(kT)}
\tag{7}
" alt="Z=\sum_{j=1}^\infty g_je^{-(E_j-E_1)/(kT)}
\tag{7}
" class="ee_img tr_noresize" eeimg="1">
对处于电离初始态与最终态的原子使用配分函数 <img src="https://www.zhihu.com/equation?tex=Z_i" alt="Z_i" class="ee_img tr_noresize" eeimg="1"> , <img src="https://www.zhihu.com/equation?tex=Z_{i+1}" alt="Z_{i+1}" class="ee_img tr_noresize" eeimg="1"> （**对于不同电离态的原子，其电子分布的配分函数也是不同的**）：

<img src="https://www.zhihu.com/equation?tex=\frac{N_{i+1}}{N_i}=\frac{2Z_{i+1}}{n_eZ_i}(\frac{2\pi m_ekT}{h^2})^{3/2}e^{-\mathcal{X_i}/kT}
\tag{8}
" alt="\frac{N_{i+1}}{N_i}=\frac{2Z_{i+1}}{n_eZ_i}(\frac{2\pi m_ekT}{h^2})^{3/2}e^{-\mathcal{X_i}/kT}
\tag{8}
" class="ee_img tr_noresize" eeimg="1">
（8）即**萨哈公式**。其中 <img src="https://www.zhihu.com/equation?tex=n_e" alt="n_e" class="ee_img tr_noresize" eeimg="1"> 是自由电子的数密度。 <img src="https://www.zhihu.com/equation?tex=Z_{i+1}" alt="Z_{i+1}" class="ee_img tr_noresize" eeimg="1"> 前的2这个因子，表明自由电子的两种可能的自旋 <img src="https://www.zhihu.com/equation?tex=m_s=\pm 1/2" alt="m_s=\pm 1/2" class="ee_img tr_noresize" eeimg="1"> 。

引入理想气体状态方程 <img src="https://www.zhihu.com/equation?tex=P_e=n_ekT" alt="P_e=n_ekT" class="ee_img tr_noresize" eeimg="1"> ，有：

<img src="https://www.zhihu.com/equation?tex=\frac{N_{i+1}}{N_i}=\frac{2kTZ_{i+1}}{P_eZ_i}(\frac{2\pi m_ekT}{h^2})^{3/2}e^{-\mathcal{X_i}/kT}
\tag{9}
" alt="\frac{N_{i+1}}{N_i}=\frac{2kTZ_{i+1}}{P_eZ_i}(\frac{2\pi m_ekT}{h^2})^{3/2}e^{-\mathcal{X_i}/kT}
\tag{9}
" class="ee_img tr_noresize" eeimg="1">
其中，电子压强的范围是从较冷恒星大气中的 <img src="https://www.zhihu.com/equation?tex=0.1N\cdot m^{-2}" alt="0.1N\cdot m^{-2}" class="ee_img tr_noresize" eeimg="1"> 到较热恒星大气中的 <img src="https://www.zhihu.com/equation?tex=100N\cdot m^{-2}" alt="100N\cdot m^{-2}" class="ee_img tr_noresize" eeimg="1"> 。

这样我们就回答了“**处在不同电离态的原子的相对数目是多少**？”这个问题。

##### 5，结合玻尔兹曼公式和萨哈公式

考虑恒星大气是由纯氢组成的，那么电离氢的占比为：

<img src="https://www.zhihu.com/equation?tex=\frac{N_{II}}{N_{total}}=\frac{N_{II}}{N_I+N_{II}}=\frac{N_{II}/N_I}{1+N_{II}/N_I}
\tag{10}
" alt="\frac{N_{II}}{N_{total}}=\frac{N_{II}}{N_I+N_{II}}=\frac{N_{II}/N_I}{1+N_{II}/N_I}
\tag{10}
" class="ee_img tr_noresize" eeimg="1">
利用萨哈公式，考虑到 <img src="https://www.zhihu.com/equation?tex=\mathrm{H\: II}" alt="\mathrm{H\: II}" class="ee_img tr_noresize" eeimg="1"> 是质子，没有简并，故 <img src="https://www.zhihu.com/equation?tex=Z_{II}=1" alt="Z_{II}=1" class="ee_img tr_noresize" eeimg="1"> ；考虑 <img src="https://www.zhihu.com/equation?tex=E_2-E_1=10.2eV \gg kT" alt="E_2-E_1=10.2eV \gg kT" class="ee_img tr_noresize" eeimg="1"> ，故玻尔兹曼因子 <img src="https://www.zhihu.com/equation?tex=e^{(E_2-E_1)/kT}\ll 1" alt="e^{(E_2-E_1)/kT}\ll 1" class="ee_img tr_noresize" eeimg="1"> ，从而几乎所有 <img src="https://www.zhihu.com/equation?tex=\mathrm{H \: I}" alt="\mathrm{H \: I}" class="ee_img tr_noresize" eeimg="1"> 都处于基态，从而 <img src="https://www.zhihu.com/equation?tex=Z_I=2\times (1)^2=2" alt="Z_I=2\times (1)^2=2" class="ee_img tr_noresize" eeimg="1"> 。

最终得到下面的图像：

![image-20240320213356077](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/氢电离态占比随温度变化曲线.png)

发现，在 <img src="https://www.zhihu.com/equation?tex=T=9600K" alt="T=9600K" class="ee_img tr_noresize" eeimg="1"> 时，一半的氢以及被电离了；上升到 <img src="https://www.zhihu.com/equation?tex=11300K" alt="11300K" class="ee_img tr_noresize" eeimg="1"> 时，有95%的氢都以 <img src="https://www.zhihu.com/equation?tex=\mathrm{H\: II}" alt="\mathrm{H\: II}" class="ee_img tr_noresize" eeimg="1"> 的形式存在。于是在这样的大约3000K的温度区间中，会发生氢的电离。恒星内部氢被部分电离的狭窄区域称为氢的**部分电离区**。

氢原子处于第一激发态的占比可以这样给出：

<img src="https://www.zhihu.com/equation?tex=\frac{N_2}{N_{total}}=(\frac{N_2}{N_1+N_2})(\frac{N_1}{N_{total}})=(\frac{N_2/N_1}{1+N_2/N_1})(\frac{1}{1+N_{II}/N_I})
\tag{11}
" alt="\frac{N_2}{N_{total}}=(\frac{N_2}{N_1+N_2})(\frac{N_1}{N_{total}})=(\frac{N_2/N_1}{1+N_2/N_1})(\frac{1}{1+N_{II}/N_I})
\tag{11}
" class="ee_img tr_noresize" eeimg="1">
可以画出下面的图像：

![image-20240320214324156](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/氢的第一激发态占比随温度变化曲线.png)

**在9900K会产生氢最强的巴耳末线，而更高的温度时，氢会快速电离**。

以上的讨论是基于 <img src="https://www.zhihu.com/equation?tex=P_e=20N\cdot m^{-2}" alt="P_e=20N\cdot m^{-2}" class="ee_img tr_noresize" eeimg="1"> 。

当然恒星大气不可能只有纯氢组成。通常**每10个氢原子对应1个氦原子**。电离氦提供了更多的电子，**于是为了避免氢离子与这些电子结合，通常需要更高的温度**。

![image-20240320214944469](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/不同温度下氢原子中电子的位置.png)

这里再次强调，玻尔兹曼公式用于处于**特定电离状态的不同激发态**的原子数比值；萨哈公式用于处于**只相差一个电子的不同电离态**的原子数比值。

上图，（a）中电子处于基态，（b）中电子处于第一激发态，（c）中电子处于电离态。

还要再补充一点：萨哈公式只能应用于热动平衡的气体，满足麦克斯韦—玻尔兹曼速度分布。并且气体的密度不能过大，否则相邻离子间的相互作用不可忽略，会扭曲原子轨道，降低电离能。

Cecilia Rayne 是第一个确定恒星成分并发现氢在宇宙中占主导的人。她计算了恒星大气中，18种元素的相对丰度：

![image-20240320215706679](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/谱线强度与温度的依赖关系.png)

### 二，赫兹伯隆—罗素图

##### 1，恒星半径的巨大范围

赫兹伯隆发现了恒星的绝对星等与光谱型的相关性，他将更亮的恒星称为巨星，这是由斯特藩·玻尔兹曼公式直观得出的结论：

<img src="https://www.zhihu.com/equation?tex=R=\frac{1}{T_e^2}\sqrt\frac{L}{4\pi \sigma}
\tag{12}
" alt="R=\frac{1}{T_e^2}\sqrt\frac{L}{4\pi \sigma}
\tag{12}
" class="ee_img tr_noresize" eeimg="1">
与此同时，罗素独立地得到了与赫兹伯隆类似的结论，并用矮星来描述相对暗淡的恒星。他在下图中记录了恒星的观测特征——水平方向是光谱型，竖直方向是绝对星等。

![image-20240321085358991](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/罗素画出的第一张图.png)

图中大多数恒星都位于从左上角延伸到右下角的带中，其中左上角分布的是炽热的，明亮的O型星，右下角则是冷的，暗淡的M型星。

下图是改进后的观测者眼中的赫罗图：

![image-20240321090818705](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/观测者-赫罗图.png)

描绘的是恒星的绝对视星等与其色指数和光谱型之间的关系。

理论学家更常用温度和光度来描述这样的关系：

![image-20240321091116274](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/理论家-赫罗图.png)

主序是一条有宽度的带：

![image-20240321091316713](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/赫罗图.png)

恒星的半径可以从赫罗图上确定。

图中出现的恒星：
Procyon B: 南河三B；
Sirius B: 天狼星B，已知最大质量的白矮星之一；
Proxima Centauri: 比邻星；
Barnard's Star: 巴纳德星，距离地球6光年左右；
Sirius: 天狼星；
Spica: 角宿一；
Rigel: 参宿七；
Deneb: 天津四；
Betelgeuse: 参宿四；
Antares: 心宿二；
Aldebaran: 毕宿五。

赫罗图上的等半径线：

<img src="https://www.zhihu.com/equation?tex=M-M_{\odot} = -2.5\log (L/L_\odot)=-5\log(R/R_\odot)-10\log(T/T_\odot)
\tag{13}
" alt="M-M_{\odot} = -2.5\log (L/L_\odot)=-5\log(R/R_\odot)-10\log(T/T_\odot)
\tag{13}
" class="ee_img tr_noresize" eeimg="1">
即有：

<img src="https://www.zhihu.com/equation?tex=\log(R/R_\odot)=8.47-0.2M-2\log T
\tag{14}
" alt="\log(R/R_\odot)=8.47-0.2M-2\log T
\tag{14}
" class="ee_img tr_noresize" eeimg="1">
在图中表现为：

![image-20240321091655414](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/赫罗图-等半径线.png)

根据恒星的质量与半径，我们可以估算恒星的密度。结果发现，主序星的密度与水的密度相当；更大半径，更大质量的早型星的平均密度反而更低。

##### 2，摩根—基南光度分类（Morgan-Keenan）

哈弗光谱分类不能唯一确定恒星的光谱性质以及在赫罗图上的位置。后来摩根和基南根据**特征谱线宽度的变化**对恒星再进行分类。在哈佛光谱后加上罗马数字。数字越大表示谱线越宽。

![image-20240321092649263](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/恒星光谱分类/基南和摩根的分类.png)

MKK图建立了二维的摩根—基南（M-K）光谱分类系统。这也称为叶凯士光谱分类。它也能够反映恒星光度的高低，这是因为谱线的压力致宽：恒星大气的密度和压力越高，原子碰撞越频繁，从而导致产生的谱线越宽。光度级数值越小，表明恒星的光度越高。下表是摩根—基南光度分类：

| 分类 |  恒星类型  |

| :--: | :--------: |

|  Ia  | 最亮超巨星 |

|  Ib  | 次亮超巨星 |

|  II  |   亮巨星   |

| III  |    巨星    |

|  IV  |   亚巨星   |

|  V   |    矮星    |

|  VI  |   亚矮星   |

| VII  |   白矮星   |


并且我们从赫罗图上的纵坐标得到恒星的绝对星等M后，再根据视星等m，和星等计算公式，可以得到恒星的距离：

<img src="https://www.zhihu.com/equation?tex=d=10^{(m-M+5)/5}
\tag{15}
" alt="d=10^{(m-M+5)/5}
\tag{15}
" class="ee_img tr_noresize" eeimg="1">
其中d的单位是秒差距（pc）。这种测距方法称为**光谱（分光）视差法**。

结合哈佛光谱分类和光度级分类，可以得到**恒星的二元光谱分类**：例如太阳的光谱型：G2V。
