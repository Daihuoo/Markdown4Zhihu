# 双星系统与恒星参数

本书第二部分的目标是详细了解恒星的结构与演化，为此我们要掌握恒星物理特性的知识。此前我们可以通过**黑体辐射曲线，光谱，视差等**，确定**恒星的有效温度，光度，半径等**其他参数，从而可以估算恒星的质量等性质。但最直接测量恒星质量的方式还是利用恒星之间的引力相互作用。

宇宙创造了这样一个环境——**天空中大多数恒星都属于多星系统**，两颗或者更多的恒星围绕着一个共同的质心运动。为此，计算这些多星系统的轨道参数并分析，可以得到恒星的诸多性质。

### 一，双星的分类

根据双星的具体观测特征，可以分为以下几类：

1. 光学双星，optical double：具有相似的赤经赤纬，在视线方向上像是双星，但实际并没有引力将它们束缚在一起。

2. 目视双星，visual binary：两颗恒星都可以独立地分辨出来，有可能监测到成员星的运动。

3. 天体测量双星，astrometric binary：双星中的一颗比另一颗亮很多，暗的星难以被直接观测。但是由于引力相互作用，可以从亮星观测到的振荡运动说明暗星的存在。

4. 食双星，eclipsing binary：轨道面近似沿着观测者的视线，导致一颗星可能周期性地从另一颗星的面前经过，遮挡被食星的光线。可以通过望远镜接受到的光线总量变换推断。

5. 光谱双星，spectrum binary：光谱双星是一个具有两个叠加的，独立的，可分辨光谱的系统。如果恒星的径向速度不为零，那么多普勒效应会起作用，使得观测得到的谱线与静止系之间存在偏移。容易知道，当其中一颗恒星的谱线蓝移的时候，另一颗的谱线必定红移，这是因为它们在绕一个质心做周期性的运动。分析这两组叠加的光谱，可以确认其双星的身份。

6. 分光双星，spectroscopic binary：如果双星系统的周期不是特别长，轨道运动有视线方向上的分量，那么可以观测到谱线的周期性移动。下图展示了轨道运动中不同相位时的谱线波长相对位置。

   ![image-20240320144410492](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/双星系统与恒星参数/双线分光双星谱线的周期性移动.png)

   如图所示，在（a）的情况下，恒星1靠近地球运动，恒星2远离地球运动，那么1的谱线蓝移，2的谱线红移，从而造成了右列第一个图像的光谱分布图。其他情况类似分析。



### 二，利用目视双星确定质量

假设轨道平面垂直于观测者视线，对于双星系统，选用质心参考系，有，

<img src="https://www.zhihu.com/equation?tex=\frac{m_1\mathbf{r_1}+m_2\mathbf{r_2}}{m_1+m_2} = 0
\tag{1}
" alt="\frac{m_1\mathbf{r_1}+m_2\mathbf{r_2}}{m_1+m_2} = 0
\tag{1}
" class="ee_img tr_noresize" eeimg="1">
只考虑位矢大小，有，

<img src="https://www.zhihu.com/equation?tex=\frac{m_1}{m_2}=\frac{a_2}{a_1}=\frac{a_2}{a_1}
\tag{2}
" alt="\frac{m_1}{m_2}=\frac{a_2}{a_1}=\frac{a_2}{a_1}
\tag{2}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=a_1,a_2" alt="a_1,a_2" class="ee_img tr_noresize" eeimg="1"> 分别是两颗恒星运动轨道的半长轴。设观测者到双星系统的距离为 <img src="https://www.zhihu.com/equation?tex=d" alt="d" class="ee_img tr_noresize" eeimg="1"> ，那么有，

<img src="https://www.zhihu.com/equation?tex=\alpha_1=\frac{a_1}{d} \quad \alpha_2=\frac{a_2}{d}
\tag{3}
" alt="\alpha_1=\frac{a_1}{d} \quad \alpha_2=\frac{a_2}{d}
\tag{3}
" class="ee_img tr_noresize" eeimg="1">
于是质量比转换为，

<img src="https://www.zhihu.com/equation?tex=\frac{m_1}{m_2}=\frac{\alpha_2}{\alpha_1}
\tag{4}
" alt="\frac{m_1}{m_2}=\frac{\alpha_2}{\alpha_1}
\tag{4}
" class="ee_img tr_noresize" eeimg="1">
由开普勒第三定律，

<img src="https://www.zhihu.com/equation?tex=P^2=\frac{4\pi^2}{G(m_1+m_2)}a^3
\tag{5}
" alt="P^2=\frac{4\pi^2}{G(m_1+m_2)}a^3
\tag{5}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> 是一个轨道周期， <img src="https://www.zhihu.com/equation?tex=a" alt="a" class="ee_img tr_noresize" eeimg="1"> 是折合质量的轨道半长轴 <img src="https://www.zhihu.com/equation?tex=a=a_1+a_2" alt="a=a_1+a_2" class="ee_img tr_noresize" eeimg="1"> 。轨道周期也是可测量的量，前一小节提到的双星分类中周期性观测到的量，计算轨道周期。

当轨道平面与天空平面之间的夹角为 <img src="https://www.zhihu.com/equation?tex=i" alt="i" class="ee_img tr_noresize" eeimg="1"> 时，如下图：

![image-20240320150416806](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/双星系统与恒星参数/真实椭圆轨道投影到天空平面.png)

**lines of nodes**表示**节线**，图中是轨道平面与天空平面沿平行于短轴的直线相交的情况。

轨道夹角对质量比无影响，因为：

<img src="https://www.zhihu.com/equation?tex=\frac{m_1}{m_2}=\frac{\alpha_2}{\alpha_2}=\frac{\alpha_2 \cos i}{\alpha_1 \cos i}=\frac{\alpha_2^*}{\alpha_1^*}
\tag{6}
" alt="\frac{m_1}{m_2}=\frac{\alpha_2}{\alpha_2}=\frac{\alpha_2 \cos i}{\alpha_1 \cos i}=\frac{\alpha_2^*}{\alpha_1^*}
\tag{6}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=\alpha_1^*,\alpha_2^*" alt="\alpha_1^*,\alpha_2^*" class="ee_img tr_noresize" eeimg="1"> 是直接观测到的夹角。

但对开普勒第三定律有影响：

<img src="https://www.zhihu.com/equation?tex=m_1+m_2=\frac{4\pi^2}{G}\frac{(ad)^{3}}{P^2}=\frac{4\pi^2}{G}(\frac{d}{\cos i})\frac{a^{*3}}{P^2}
\tag{7}
" alt="m_1+m_2=\frac{4\pi^2}{G}\frac{(ad)^{3}}{P^2}=\frac{4\pi^2}{G}(\frac{d}{\cos i})\frac{a^{*3}}{P^2}
\tag{7}
" class="ee_img tr_noresize" eeimg="1">

### 三，食分光双星

##### 1，偏心率对径向速度测量的影响

倾角 <img src="https://www.zhihu.com/equation?tex=i" alt="i" class="ee_img tr_noresize" eeimg="1"> 会影响径向速度的测量。如上图，我们有，

<img src="https://www.zhihu.com/equation?tex=v_{1r}^{max}=v_1\sin i \\
v_{2r}^{max}=v_2\sin i
\tag{8}
" alt="v_{1r}^{max}=v_1\sin i \\
v_{2r}^{max}=v_2\sin i
\tag{8}
" class="ee_img tr_noresize" eeimg="1">
其中 <img src="https://www.zhihu.com/equation?tex=v_{1r}^{max},v_{2r}^{max}" alt="v_{1r}^{max},v_{2r}^{max}" class="ee_img tr_noresize" eeimg="1"> 分别是观测到的两恒星最大的径向速度。

![image-20240320152029440](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/双星系统与恒星参数/圆形轨道.png)

如图是圆形轨道（ <img src="https://www.zhihu.com/equation?tex=e=0" alt="e=0" class="ee_img tr_noresize" eeimg="1"> ）中两颗恒星的轨道路径与径向速度。右图纵坐标表示径向速度，成三角函数周期性变换，与左图相吻合。

如果 <img src="https://www.zhihu.com/equation?tex=e\neq 0" alt="e\neq 0" class="ee_img tr_noresize" eeimg="1"> ，那么观测到的速度曲线将变得歪斜。

![image-20240320152350736](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/双星系统与恒星参数/椭圆轨道.png)

如图是椭圆轨道（ <img src="https://www.zhihu.com/equation?tex=e=0.4" alt="e=0.4" class="ee_img tr_noresize" eeimg="1"> ）的情形。

##### 2，质量函数与质量—光度关系

当偏心率足够小的时候（ <img src="https://www.zhihu.com/equation?tex=e\ll 1" alt="e\ll 1" class="ee_img tr_noresize" eeimg="1"> ），即近似可看成圆轨道，恒星速率基本恒定。那考虑轨道倾角后，有 <img src="https://www.zhihu.com/equation?tex=v_{1r}=v_1\sin i,v_{2r}=v_2 \sin i" alt="v_{1r}=v_1\sin i,v_{2r}=v_2 \sin i" class="ee_img tr_noresize" eeimg="1"> ，从而得到质量之比的关系：

<img src="https://www.zhihu.com/equation?tex=\frac{m_1}{m_2}=\frac{v_2}{v_1}=\frac{v_{2r}}{v_{1r}}
\tag{9}
" alt="\frac{m_1}{m_2}=\frac{v_2}{v_1}=\frac{v_{2r}}{v_{1r}}
\tag{9}
" class="ee_img tr_noresize" eeimg="1">
同理，我们有：

<img src="https://www.zhihu.com/equation?tex=a=a_1+a_2=\frac{P}{2\pi}(v_1+v_2)
\tag{10}
" alt="a=a_1+a_2=\frac{P}{2\pi}(v_1+v_2)
\tag{10}
" class="ee_img tr_noresize" eeimg="1">
求解质量之和：

<img src="https://www.zhihu.com/equation?tex=m_1+m_2=\frac{P}{2\pi G}\frac{(v_{1r}+v_{2r})^3}{\sin^3 i}
\tag{11}
" alt="m_1+m_2=\frac{P}{2\pi G}\frac{(v_{1r}+v_{2r})^3}{\sin^3 i}
\tag{11}
" class="ee_img tr_noresize" eeimg="1">
但如果只能观测到亮星，可以将（9）代入（11），消去暗星观测到的径向速度 <img src="https://www.zhihu.com/equation?tex=v_{2r}" alt="v_{2r}" class="ee_img tr_noresize" eeimg="1"> ，有：

<img src="https://www.zhihu.com/equation?tex=\frac{m_2^3}{(m_1+m_2)^2}\sin^3 i =\frac{P}{2\pi G}v_{1r}^3
\tag{12}
" alt="\frac{m_2^3}{(m_1+m_2)^2}\sin^3 i =\frac{P}{2\pi G}v_{1r}^3
\tag{12}
" class="ee_img tr_noresize" eeimg="1">
（12）的右侧称为**质量函数**。

在不知道 <img src="https://www.zhihu.com/equation?tex=i" alt="i" class="ee_img tr_noresize" eeimg="1"> 的情况下，无法得到 <img src="https://www.zhihu.com/equation?tex=m_1,m_2" alt="m_1,m_2" class="ee_img tr_noresize" eeimg="1"> 的精确值。恒星可以根据它们的有效温度与光度进行分组。选择 <img src="https://www.zhihu.com/equation?tex=\sin^3 i" alt="\sin^3 i" class="ee_img tr_noresize" eeimg="1"> 的适当平均值，可以找到上述分组后每一类恒星的统计质量估计。

![image-20240320154040135](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/双星系统与恒星参数/质量—光度关系图.png)

##### 3，利用食来确定半径和温度比

食双星系统意味着 <img src="https://www.zhihu.com/equation?tex=i" alt="i" class="ee_img tr_noresize" eeimg="1"> 必须接近90°。

![image-20240320155706336](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/双星系统与恒星参数/倾角为90°时的光变曲线.png)

如上图，观测者垂直于纸面，假设较小的恒星比较大的恒星更热。当较小的恒星从a移动到b时，亮度迅速下降。b移动到c这段过程中，较小的恒星完全被较大的恒星遮掩，亮度几乎保持不变。同理从f移动到g过程中，小恒星遮挡部分大恒星，但是由于小恒星更热，导致这一段的亮度要比小恒星被遮挡时更亮一些。

可以通过首次接触到光极小之间的时间，与恒星运动的速度，计算出成员星的半径。例如小恒星的半径:

<img src="https://www.zhihu.com/equation?tex=r_s=\frac{v}{2}(t_a-t_b)
\tag{13}
" alt="r_s=\frac{v}{2}(t_a-t_b)
\tag{13}
" class="ee_img tr_noresize" eeimg="1">
 <img src="https://www.zhihu.com/equation?tex=v=v_s+v_l" alt="v=v_s+v_l" class="ee_img tr_noresize" eeimg="1"> 是两颗恒星的相对速度。那么大恒星的半径：

<img src="https://www.zhihu.com/equation?tex=r_l=\frac{v}{2}(t_c-t_a)
\tag{14}
" alt="r_l=\frac{v}{2}(t_c-t_a)
\tag{14}
" class="ee_img tr_noresize" eeimg="1">
![image-20240320160146671](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/双星系统与恒星参数/部分食双星的光变曲线.png)

上图展示的情况是 <img src="https://www.zhihu.com/equation?tex=i<" alt="i<" class="ee_img tr_noresize" eeimg="1"> 90°，且恒星没有完全被遮挡的情况。那么亮度的极小值不再是恒定的。

对于倾角为90°时的情况，假设辐射表面流量：

<img src="https://www.zhihu.com/equation?tex=F_r=F_{surf}=\sigma T_e^4
\tag{15}
" alt="F_r=F_{surf}=\sigma T_e^4
\tag{15}
" class="ee_img tr_noresize" eeimg="1">
当两颗星都可见时，辐射为：

<img src="https://www.zhihu.com/equation?tex=B_0=k(\pi r_l^2F_{rl}+\pi r_s^2F_{rs})
\tag{16}
" alt="B_0=k(\pi r_l^2F_{rl}+\pi r_s^2F_{rs})
\tag{16}
" class="ee_img tr_noresize" eeimg="1">
主极小期（热的小恒星被完全遮挡）：

<img src="https://www.zhihu.com/equation?tex=B_p=k\pi r_l^2F_{rl}
\tag{17}
" alt="B_p=k\pi r_l^2F_{rl}
\tag{17}
" class="ee_img tr_noresize" eeimg="1">
次极小期（大恒星被部分遮挡）：

<img src="https://www.zhihu.com/equation?tex=B_s=k(\pi r_l^2-\pi r_s^2)F_{rl}+k\pi r_s^2F_{rs}
\tag{18}
" alt="B_s=k(\pi r_l^2-\pi r_s^2)F_{rl}+k\pi r_s^2F_{rs}
\tag{18}
" class="ee_img tr_noresize" eeimg="1">
从而有：

<img src="https://www.zhihu.com/equation?tex=\frac{B_0-B_p}{B_0-B_s}=(\frac{T_s}{T_l})^4
\tag{19}
" alt="\frac{B_0-B_p}{B_0-B_s}=(\frac{T_s}{T_l})^4
\tag{19}
" class="ee_img tr_noresize" eeimg="1">

### 四，总结

双星系统中，测量恒星质量的先决条件是 <img src="https://www.zhihu.com/equation?tex=a,P" alt="a,P" class="ee_img tr_noresize" eeimg="1"> 的测量。也就是**轨道半长轴与轨道周期**。

对于**目视双星**，**恒星位置与运动**很关键。如果知道子星的最大和最小角间距，以及距离双星的距离，那么可以算出轨道半长径的大小。（ <img src="https://www.zhihu.com/equation?tex=a=(\alpha_1+\alpha_2)d/2" alt="a=(\alpha_1+\alpha_2)d/2" class="ee_img tr_noresize" eeimg="1"> ）进而利用开普勒第三定律以及轨道周期求解质量。

对于**分光双星**，**谱线的多普勒效应**很关键。谱线位移量与轨道运动速度以及双星的轨道倾角有关。例如前面提到的视向速度曲线。最终可以得到质量函数。

对于**食双星**，**光变曲线**的测量很关键。由光变曲线可以测量两颗子星的温度比，轨道倾角，恒星大小。
