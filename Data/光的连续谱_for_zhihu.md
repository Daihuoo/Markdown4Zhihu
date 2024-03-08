# 光的连续谱

我们知道光的本质是电磁波。而电磁辐射是以变化的电磁场传递能量、具有特定波长和强度的波。人们获取天体信息的主要渠道有四种：电磁辐射，宇宙线，中微子，引力波。而其中，电磁辐射对天文学的研究尤为重要。

### 一，恒星视差

对于遥远恒星发出的光，我们能够直观测量的包括亮度等。测量恒星的固有亮度与确定它们的距离密不可分，于是天体距离测量这一重要且艰难的问题便被提出了。只有测量了天体的距离，才能进一步得到天体的光度、质量和大小等物理量。

* **三角视差法 trigonometric parallax**：

  **视差**，即天体对某一**基线**所张的角度，即位于基线两端观察天体在背景上的位置变化。

  **周年视差**，是以**地球公转轨道的半长径**作为基线测量恒星的距离。容易想象，对于遥远恒星组成的背景具有周年性的变化，于是就有了四季星空的变化。这是因为虽然遥远恒星有自身的运动，但在地球上观察者的角度来看，这种自行的变化并非周期性的，于是能够与由于地球轨道运动引起的恒星周期性位移区分开来。

  ![image-20240306193300278](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/光的连续谱/image-20240306193300278.png)

  设距离为 <img src="https://www.zhihu.com/equation?tex=d" alt="d" class="ee_img tr_noresize" eeimg="1"> ，视差为 <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> ，那么有：

<img src="https://www.zhihu.com/equation?tex=d=\frac{1\mathrm{AU}}{\tan p} \approx\frac{1}{p}\mathrm{AU}\approx \frac{206265}{p''}\mathrm{AU}=\frac{1}{p''}\mathrm{pc}
  " alt="d=\frac{1\mathrm{AU}}{\tan p} \approx\frac{1}{p}\mathrm{AU}\approx \frac{206265}{p''}\mathrm{AU}=\frac{1}{p''}\mathrm{pc}
  " class="ee_img tr_noresize" eeimg="1">
  其中定义**秒差距**：当视差角为 <img src="https://www.zhihu.com/equation?tex=1''" alt="1''" class="ee_img tr_noresize" eeimg="1"> 的时候，恒星的距离为 <img src="https://www.zhihu.com/equation?tex=1\mathrm{pc}" alt="1\mathrm{pc}" class="ee_img tr_noresize" eeimg="1"> 。光年为光一年走过的距离，记作 <img src="https://www.zhihu.com/equation?tex=\mathrm{ly}" alt="\mathrm{ly}" class="ee_img tr_noresize" eeimg="1"> （light-yera），那么有关系： <img src="https://www.zhihu.com/equation?tex=1\mathrm{pc}\approx3.26\mathrm{ly}\approx206265\mathrm{AU}" alt="1\mathrm{pc}\approx3.26\mathrm{ly}\approx206265\mathrm{AU}" class="ee_img tr_noresize" eeimg="1"> 。

* 然而视差法的适用范围取决于望远镜的空间分辨率，因此恒星三角视差法只适用于测量太阳附近的恒星的距离。

  对于更加遥远的恒星，可能考虑利用赫罗图，造父变星，Ia型超新星，哈勃定律等测量天体之间的距离。

### 二，星等大小

描述恒星辐射的强弱有不同的方法。

* **光度， <img src="https://www.zhihu.com/equation?tex=L" alt="L" class="ee_img tr_noresize" eeimg="1"> ，luminosity**：天体在**单位时间内辐射的总能量**。因此可知，光度是恒星的固有量。单位是 <img src="https://www.zhihu.com/equation?tex=J\cdot s^{-1}" alt="J\cdot s^{-1}" class="ee_img tr_noresize" eeimg="1"> ，天文中常用 <img src="https://www.zhihu.com/equation?tex=erg\cdot s^{-1}" alt="erg\cdot s^{-1}" class="ee_img tr_noresize" eeimg="1"> ，其中 <img src="https://www.zhihu.com/equation?tex=1erg=10^{-7}J" alt="1erg=10^{-7}J" class="ee_img tr_noresize" eeimg="1"> 。

* **流量， <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> ，flux**：天体在**单位时间单位面积辐射的总能量**。对于地球观测者而言，是在地球上单位时间内单位面积上接受到的总能量，是我们可以直接测量得到的量。这也称为天体的**亮度**。单位是 <img src="https://www.zhihu.com/equation?tex=W\cdot m^{-2}\cdot s^{-1}" alt="W\cdot m^{-2}\cdot s^{-1}" class="ee_img tr_noresize" eeimg="1"> ，天文上也常用 <img src="https://www.zhihu.com/equation?tex=erg\cdot cm^{-2}\cdot s^{-1}" alt="erg\cdot cm^{-2}\cdot s^{-1}" class="ee_img tr_noresize" eeimg="1"> 。

  单色流量是指在**单位频率**上的流量，即有积分关系：

<img src="https://www.zhihu.com/equation?tex=F=\int_0^\infty F_\nu d\nu
  " alt="F=\int_0^\infty F_\nu d\nu
  " class="ee_img tr_noresize" eeimg="1">
  类似的可以定义单色光度。

  假设观测者距离恒星距离为 <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> ，那么流量与光度具有以下的关系，

<img src="https://www.zhihu.com/equation?tex=F=\frac{L}{4\pi R^2}
  " alt="F=\frac{L}{4\pi R^2}
  " class="ee_img tr_noresize" eeimg="1">
  这也就是光的平方反比定律。

* **辐射强度， <img src="https://www.zhihu.com/equation?tex=I" alt="I" class="ee_img tr_noresize" eeimg="1"> ，intensity**：天体在**单位时间单位面积单位立体角**辐射的能量，对于单色强度，在以上的基础上再加上单位频率内这一条件。那么其单位为 <img src="https://www.zhihu.com/equation?tex=erg\cdot cm^{-2}\cdot s^{-1}\cdot sr^{-1}" alt="erg\cdot cm^{-2}\cdot s^{-1}\cdot sr^{-1}" class="ee_img tr_noresize" eeimg="1"> 。

* 太阳的光度为 <img src="https://www.zhihu.com/equation?tex=L_\bigodot=3.839 \times 10^{26}W" alt="L_\bigodot=3.839 \times 10^{26}W" class="ee_img tr_noresize" eeimg="1"> ，在地球大气上方接收到的辐射能量为 <img src="https://www.zhihu.com/equation?tex=F=1365W\cdot m^{-2}" alt="F=1365W\cdot m^{-2}" class="ee_img tr_noresize" eeimg="1"> ，这个辐射能量值被称为太阳辐照度，有时也称为太阳常数。

在此基础上，我们可以定义视星等与绝对星等，以及找到它们与光度，流量之间的联系。

* **视星等，apparent magnitude**：古希腊天文学家依巴谷发明了一种数字标度来描述每颗恒星在天空中出现的明亮程度。他给最亮的恒星的视星等定为 <img src="https://www.zhihu.com/equation?tex=m=1" alt="m=1" class="ee_img tr_noresize" eeimg="1"> ，最暗的定为 <img src="https://www.zhihu.com/equation?tex=m=6" alt="m=6" class="ee_img tr_noresize" eeimg="1"> 。

  现代改善了这一定义：星等差为5正好相当于亮度比为100，即每相差1等，亮度比相差2.512倍。

  即有，

<img src="https://www.zhihu.com/equation?tex=m_2-m_1=-2.5\lg\frac{F_2}{F_1}
  " alt="m_2-m_1=-2.5\lg\frac{F_2}{F_1}
  " class="ee_img tr_noresize" eeimg="1">

* **绝对星等，absolute magnitude**：绝对星等定义为位于 <img src="https://www.zhihu.com/equation?tex=10\mathrm{pc}" alt="10\mathrm{pc}" class="ee_img tr_noresize" eeimg="1"> 处的天体视星等，即有，

<img src="https://www.zhihu.com/equation?tex=m-M=-2.5\lg \frac{F(r)}{F(10)}=5\lg \frac{r}{10}
  " alt="m-M=-2.5\lg \frac{F(r)}{F(10)}=5\lg \frac{r}{10}
  " class="ee_img tr_noresize" eeimg="1">
  其中 <img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1"> 表示绝对星等， <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> 单位为秒差距，化简利用了光度与辐射流量之间的关系。

* **距离模数，the distance modules**：由视星等以及绝对星等的定义可计算出，

<img src="https://www.zhihu.com/equation?tex=r=10^{(m-M+5)/5}\mathrm{pc}
  " alt="r=10^{(m-M+5)/5}\mathrm{pc}
  " class="ee_img tr_noresize" eeimg="1">
  于是 <img src="https://www.zhihu.com/equation?tex=m-M" alt="m-M" class="ee_img tr_noresize" eeimg="1"> 可以度量恒星距离，称为距离模数。

* 太阳：

<img src="https://www.zhihu.com/equation?tex=m_{Sun}=-26.83 \quad M_{Sun}=+4.74
  " alt="m_{Sun}=-26.83 \quad M_{Sun}=+4.74
  " class="ee_img tr_noresize" eeimg="1">
  满月：

<img src="https://www.zhihu.com/equation?tex=m_{Moon}=-12.74
  " alt="m_{Moon}=-12.74
  " class="ee_img tr_noresize" eeimg="1">

### 三，光的波动本质

* **杨氏双缝实验**：现在我们都知道光具有波粒二象性，但此前关于光究竟是粒子还是波的问题一直是科学家间的争议。

  根据**惠更斯**的观点，光可用波的物理量来描述。那么光速定义为：

<img src="https://www.zhihu.com/equation?tex=c=\lambda \nu
  " alt="c=\lambda \nu
  " class="ee_img tr_noresize" eeimg="1">
  即光波波长与频率的乘积。

  后来**托马斯·杨**的双缝干涉实验证明了光的波动性。波长为 <img src="https://www.zhihu.com/equation?tex=\lambda" alt="\lambda" class="ee_img tr_noresize" eeimg="1"> 的单色光通过双缝后，在屏幕上能够观察到一系列**明暗相间的干涉条纹**。这是因为光经过狭缝后，会发生衍射，即光波会四处散开。而又由于光的叠加原理，最终会产生干涉现象。

  当波峰与波峰，或波谷与波谷相遇时，会导致相长干涉；波峰与波谷相遇则会导致相消干涉。这都是由于两波的相位差导致的。

  ![image-20240306212540946](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/光的连续谱/image-20240306212540946.png)

  当 <img src="https://www.zhihu.com/equation?tex=L\gg d" alt="L\gg d" class="ee_img tr_noresize" eeimg="1"> 时，光程差近似为 <img src="https://www.zhihu.com/equation?tex=d\sin \theta" alt="d\sin \theta" class="ee_img tr_noresize" eeimg="1"> ，那么**明条纹**对应 <img src="https://www.zhihu.com/equation?tex=d\sin\theta=n\lambda" alt="d\sin\theta=n\lambda" class="ee_img tr_noresize" eeimg="1"> ；**暗条纹**对应于 <img src="https://www.zhihu.com/equation?tex=d\sin\theta=(n+\frac{1}{2})\lambda" alt="d\sin\theta=(n+\frac{1}{2})\lambda" class="ee_img tr_noresize" eeimg="1"> ，其中 <img src="https://www.zhihu.com/equation?tex=n=0,1,2,\cdots" alt="n=0,1,2,\cdots" class="ee_img tr_noresize" eeimg="1"> 。

* **麦克斯韦的电磁波理论**：

  十九世纪六十年代，麦克斯韦浓缩出了**麦克斯韦方程组**。其中的四个关于电场磁场的方程，预言了电磁波的存在。

<img src="https://www.zhihu.com/equation?tex=\begin{align}
      \nabla \cdot \mathbf{E} &= \frac{\rho}{\varepsilon_0} \\
      \nabla \cdot \mathbf{B} &= 0 \\
      \nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
      \nabla \times \mathbf{B} &= \mu_0 \mathbf{J} + \mu_0 \varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}
  \end{align}
  " alt="\begin{align}
      \nabla \cdot \mathbf{E} &= \frac{\rho}{\varepsilon_0} \\
      \nabla \cdot \mathbf{B} &= 0 \\
      \nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
      \nabla \times \mathbf{B} &= \mu_0 \mathbf{J} + \mu_0 \varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}
  \end{align}
  " class="ee_img tr_noresize" eeimg="1">
  根据他的理论，电磁波在真空中的传播速度为 <img src="https://www.zhihu.com/equation?tex=v=1/\sqrt{\varepsilon_0 \mu_0}" alt="v=1/\sqrt{\varepsilon_0 \mu_0}" class="ee_img tr_noresize" eeimg="1"> ，发现这与测量得到的光速相当吻合。另外还发现电磁波的性质也与光波的性质吻合，包括但不限于横波，偏振等。

  后来赫兹在实验室中成功产生了无线电波。

  ![image-20240306214431820](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/光的连续谱/image-20240306214431820.png)

* **电磁波谱**：可见光仅仅对应于电磁波谱中的一小段波长范围。

  不同波长对应的电磁波有着不同的性质，且对应于宇宙中不同的天体以及现象。研究不同波段的光谱，是我们认识宇宙研究天文学的优质研究手段。

  ![image-20240306214932325](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/光的连续谱/image-20240306214932325.png)

* **玻印亭矢量和辐射压**：

  电磁波在传播的方向上携带能量和动量。我们可以用**玻印亭矢量**描述电磁波在传播方向上单位时间单位面积内携带的能量。用 <img src="https://www.zhihu.com/equation?tex=S" alt="S" class="ee_img tr_noresize" eeimg="1"> 表示，有，

<img src="https://www.zhihu.com/equation?tex=\mathbf{S}=\frac{1}{\mu_0}\mathbf{E}\times \mathbf{B}
  " alt="\mathbf{S}=\frac{1}{\mu_0}\mathbf{E}\times \mathbf{B}
  " class="ee_img tr_noresize" eeimg="1">
   <img src="https://www.zhihu.com/equation?tex=E,B" alt="E,B" class="ee_img tr_noresize" eeimg="1"> 的变化是正弦型的，对于能量来说，应当关注电磁波在一个周期上的平均值。在真空中，玻印亭矢量的时间平均值的大小为，

<img src="https://www.zhihu.com/equation?tex=\langle S \rangle = \frac{1}{2\mu_0}E_0B_0
  " alt="\langle S \rangle = \frac{1}{2\mu_0}E_0B_0
  " class="ee_img tr_noresize" eeimg="1">
   <img src="https://www.zhihu.com/equation?tex=E_0,B_0" alt="E_0,B_0" class="ee_img tr_noresize" eeimg="1"> 分别是电场强度和磁感应强度的最大振幅。

  *以上详细的内容参考电磁学中的内容*

  由于电磁波携带动量，故可以在被其撞击的表面产生力的作用。据此定义**辐射压**。如果**光被完全吸收**，**辐射压产生的力在光的传播方向上**，大小为：

<img src="https://www.zhihu.com/equation?tex=F_{rad}=\frac{\langle S \rangle A}{c}\cos \theta
  " alt="F_{rad}=\frac{\langle S \rangle A}{c}\cos \theta
  " class="ee_img tr_noresize" eeimg="1">
  其中 <img src="https://www.zhihu.com/equation?tex=\theta" alt="\theta" class="ee_img tr_noresize" eeimg="1"> 是光的入射角，参考于入射表面的法线。

  如果**光被完全反射**，则**辐射压力垂直于表面的方向**；**反射光不能在平行于表面的方向上产生力**（是因为平行于表面的电场分量不会产生力的作用），大小为：

<img src="https://www.zhihu.com/equation?tex=F_{rad} = \frac{2\langle S \rangle A}{c}\cos^2\theta
  " alt="F_{rad} = \frac{2\langle S \rangle A}{c}\cos^2\theta
  " class="ee_img tr_noresize" eeimg="1">
  ![image-20240307224316588](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/光的连续谱/image-20240307224316588.png)

  在日常条件下，辐射压可忽略不计。但是在确定极端发光天体的某些行为时，辐射压力可能起到主导作用，它们同样会对星际介质中发现的小尘埃颗粒产生重大影响。

### 四，黑体辐射

热的物体发出的光的颜色和它的温度是有联系的。

* **黑体，blackbody**：黑体是处于**热动平衡状态**的**理想**天体，能够**吸收所有外来的辐射，不反射，并全部再辐射**。黑体发出的辐射称做**黑体辐射**。

  粗略近似下，恒星和行星都是黑体。温度 <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> 下的黑体在所有波段都发射具有一定能量的连续谱（温度高于0K的任何物体都会以不同的效能度发出所有波长的光）。大部分正常恒星的**连续辐射都可以近似地用黑体辐射来表示**。

* **维恩位移定律，Wien's displacement law**：黑体谱达到峰值时对应的波长与温度有一定的关系：

<img src="https://www.zhihu.com/equation?tex=\lambda_{max}T=0.002897755 \mathrm{m \cdot K}
  " alt="\lambda_{max}T=0.002897755 \mathrm{m \cdot K}
  " class="ee_img tr_noresize" eeimg="1">
  计算时常简化为，

<img src="https://www.zhihu.com/equation?tex=\lambda_{max}T=0.29 \mathrm{cm \cdot K}
  " alt="\lambda_{max}T=0.29 \mathrm{cm \cdot K}
  " class="ee_img tr_noresize" eeimg="1">
  ![image-20240307225729252](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/光的连续谱/image-20240307225729252.png)

  例如我们知道参宿四的表面温度大约为 <img src="https://www.zhihu.com/equation?tex=3600K" alt="3600K" class="ee_img tr_noresize" eeimg="1"> ，参宿七的表面温度大约为 <img src="https://www.zhihu.com/equation?tex=13000K" alt="13000K" class="ee_img tr_noresize" eeimg="1"> ，我们可以代入维恩位移公式，计算出参宿四连续谱的峰值波长大约为 <img src="https://www.zhihu.com/equation?tex=805nm" alt="805nm" class="ee_img tr_noresize" eeimg="1"> ，位于电磁谱的红外波段；参宿七的连续谱波长大约在 <img src="https://www.zhihu.com/equation?tex=223nm" alt="223nm" class="ee_img tr_noresize" eeimg="1"> ，位于紫外区域。我们观察夜空，不难发现红色的参宿四与蓝白色参宿七的鲜明区别。

* **斯特藩-玻尔兹曼公式，the Stefan-Boltzmann Equation**：斯特藩证明了面积为 <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> ，温度为 <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> 的黑体的光度 <img src="https://www.zhihu.com/equation?tex=L" alt="L" class="ee_img tr_noresize" eeimg="1"> ，

<img src="https://www.zhihu.com/equation?tex=L=A\sigma T^4
  " alt="L=A\sigma T^4
  " class="ee_img tr_noresize" eeimg="1">
  之后玻尔兹曼利用热力学定律与麦克斯韦辐射压公式推导出了这个公式，**玻尔兹曼常量**值为，

<img src="https://www.zhihu.com/equation?tex=\sigma=5.6704 \times 10^{-8} \mathrm{W\cdot m^{-2}\cdot K^{-4}}
  " alt="\sigma=5.6704 \times 10^{-8} \mathrm{W\cdot m^{-2}\cdot K^{-4}}
  " class="ee_img tr_noresize" eeimg="1">
  假设星球半径为 <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> ，则有，

<img src="https://www.zhihu.com/equation?tex=L=4\pi R^2\sigma T^4_e
  " alt="L=4\pi R^2\sigma T^4_e
  " class="ee_img tr_noresize" eeimg="1">
  其中 <img src="https://www.zhihu.com/equation?tex=T_e" alt="T_e" class="ee_img tr_noresize" eeimg="1"> 为**有效温度**。进一步可以得到恒星表面的辐射流量为，

<img src="https://www.zhihu.com/equation?tex=F_{surf}=\sigma T^4_e
  " alt="F_{surf}=\sigma T^4_e
  " class="ee_img tr_noresize" eeimg="1">
  我们知道太阳的光度与半径后，代入上式可估算太阳表面的有效温度大约为 <img src="https://www.zhihu.com/equation?tex=5777K" alt="5777K" class="ee_img tr_noresize" eeimg="1"> ，再利用维恩位移公式可以估算太阳连续谱峰值对应的波长约为 <img src="https://www.zhihu.com/equation?tex=501.6nm" alt="501.6nm" class="ee_img tr_noresize" eeimg="1"> ，在可见光波段的绿光区域。不过太阳发出的连续光有比这段波长范围更短的和更长的，最终人眼感知太阳的颜色为黄色。因为太阳辐射的大部分能量都在可见光波段，又因为地球大气在这些波段下是透明的，再加上自然选择，人眼对这部分的波长区域敏感。
  
* 新世界观的前夜：

  > “自然界和自然界的规律隐藏在黑夜里。
  > 上帝说：‘让牛顿去吧！’于是，一切成为光明。
  > 但这并没有持续下去。
  > 魔鬼咆哮着‘呵呵！让爱因斯坦去吧！’于是，一切又回到黑暗中。“

  这段两百年后的续写，道出了物理学的两次革命啊。

### 五，能量的量子化

* **瑞丽-金斯定律，Rayleigh-Jeans law**：

<img src="https://www.zhihu.com/equation?tex=B_\lambda(T)\approx\frac{2ckT}{\lambda^4}
  " alt="B_\lambda(T)\approx\frac{2ckT}{\lambda^4}
  " class="ee_img tr_noresize" eeimg="1">
  仅仅在长波波段有效，在短波区，一个无限小数目的无线短的波长意味着热炉中含有无限量的黑头辐射能量（根据经典物理学，每一份波长都都会接受到 <img src="https://www.zhihu.com/equation?tex=kT" alt="kT" class="ee_img tr_noresize" eeimg="1"> 的能量），因此被称为“**紫外灾难**”。

* **维恩公式**：

<img src="https://www.zhihu.com/equation?tex=B_\lambda(T)\approx a\lambda^{-5}e^{-b/(\lambda T)}
  " alt="B_\lambda(T)\approx a\lambda^{-5}e^{-b/(\lambda T)}
  " class="ee_img tr_noresize" eeimg="1">
  仅在短波区域成立，长波波段失效。

* **普朗克定律，Planck's Function**：

  普朗克修正了上述两个公式，找出了满足全波段的经验公式，

<img src="https://www.zhihu.com/equation?tex=B_\lambda(T)=\frac{a/\lambda^5}{e^{b/(\lambda T)}-1}
  " alt="B_\lambda(T)=\frac{a/\lambda^5}{e^{b/(\lambda T)}-1}
  " class="ee_img tr_noresize" eeimg="1">
  为了确认 <img src="https://www.zhihu.com/equation?tex=a,b" alt="a,b" class="ee_img tr_noresize" eeimg="1"> 两个常数，普朗克做出了**能量量子假说**。即有，

<img src="https://www.zhihu.com/equation?tex=\varepsilon=h\nu=\frac{hc}{\lambda}
  " alt="\varepsilon=h\nu=\frac{hc}{\lambda}
  " class="ee_img tr_noresize" eeimg="1">
  从而电磁波的能量为 <img src="https://www.zhihu.com/equation?tex=nh\nu" alt="nh\nu" class="ee_img tr_noresize" eeimg="1"> ，最终得到了**普朗克函数**：

<img src="https://www.zhihu.com/equation?tex=B_\lambda(T)=\frac{2hc^2/\lambda^5}{e^{hc/(\lambda kT)}-1}
  " alt="B_\lambda(T)=\frac{2hc^2/\lambda^5}{e^{hc/(\lambda kT)}-1}
  " class="ee_img tr_noresize" eeimg="1">
  其中 <img src="https://www.zhihu.com/equation?tex=h=6.62606876\times 10^{-34}\mathrm{J\cdot s}" alt="h=6.62606876\times 10^{-34}\mathrm{J\cdot s}" class="ee_img tr_noresize" eeimg="1"> ，即**普朗克常量**。

  我们也可以改写为，

<img src="https://www.zhihu.com/equation?tex=B_\nu(T)=\frac{2h\nu^3/c^2}{e^{h\nu/(kT)}-1}
  " alt="B_\nu(T)=\frac{2h\nu^3/c^2}{e^{h\nu/(kT)}-1}
  " class="ee_img tr_noresize" eeimg="1">

* **普朗克函数与天体物理**：温度为 <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> ，**表面积为 <img src="https://www.zhihu.com/equation?tex=dA" alt="dA" class="ee_img tr_noresize" eeimg="1"> 的黑体，单位时间内，在频率 <img src="https://www.zhihu.com/equation?tex=\nu \sim \nu+d\nu" alt="\nu \sim \nu+d\nu" class="ee_img tr_noresize" eeimg="1"> 之间，发射到立体角 <img src="https://www.zhihu.com/equation?tex=d\Omega = \sin\theta d\theta d\phi" alt="d\Omega = \sin\theta d\theta d\phi" class="ee_img tr_noresize" eeimg="1"> **中的黑体辐射能量为：

<img src="https://www.zhihu.com/equation?tex=B_\nu d\nu dA \cos\theta d\Omega =B_\nu d\nu dA \cos\theta\sin\theta d\theta d\phi
  " alt="B_\nu d\nu dA \cos\theta d\Omega =B_\nu d\nu dA \cos\theta\sin\theta d\theta d\phi
  " class="ee_img tr_noresize" eeimg="1">
  如果我们知道一颗恒星的观测特征（辐射能量、视星等，等），我们可以利用普朗克函数，计算出相应的固有性质（半径、温度，等）。

  ![image-20240308201327212](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/光的连续谱/image-20240308201327212.png)

  例如我们可以写出：

<img src="https://www.zhihu.com/equation?tex=L_\lambda d\lambda=\int_{\phi=0}^{2\pi}\int_{\theta=0}^{\pi/2}\int_A B_\lambda d\lambda dA \cos\theta\sin\theta d\theta d\phi
  " alt="L_\lambda d\lambda=\int_{\phi=0}^{2\pi}\int_{\theta=0}^{\pi/2}\int_A B_\lambda d\lambda dA \cos\theta\sin\theta d\theta d\phi
  " class="ee_img tr_noresize" eeimg="1">
  这里要注意** <img src="https://www.zhihu.com/equation?tex=\theta" alt="\theta" class="ee_img tr_noresize" eeimg="1"> 的范围**是 <img src="https://www.zhihu.com/equation?tex=0\sim \pi/2" alt="0\sim \pi/2" class="ee_img tr_noresize" eeimg="1"> ，这是因为恒星表面 <img src="https://www.zhihu.com/equation?tex=dA" alt="dA" class="ee_img tr_noresize" eeimg="1"> 的区域只会向外侧发出黑体辐射。最终算出：

<img src="https://www.zhihu.com/equation?tex=L_\lambda d\lambda=4\pi^2R^2B_{\lambda}d\lambda
  " alt="L_\lambda d\lambda=4\pi^2R^2B_{\lambda}d\lambda
  " class="ee_img tr_noresize" eeimg="1">
   <img src="https://www.zhihu.com/equation?tex=L_\lambda d\lambda" alt="L_\lambda d\lambda" class="ee_img tr_noresize" eeimg="1"> 称为**单色光度**。

  将其与**斯特藩·玻尔兹曼公式**对比，可以得到下面的关系：

<img src="https://www.zhihu.com/equation?tex=\int_0^{\infty} B_{\lambda}(T)d\lambda = \frac{\sigma T^4}{\pi}
  " alt="\int_0^{\infty} B_{\lambda}(T)d\lambda = \frac{\sigma T^4}{\pi}
  " class="ee_img tr_noresize" eeimg="1">

### 六，色指数

在第二部分的基础上，我们继续讨论星等系统。视星等的测量通常是在**某一波段范围内**进行的。而在**全波段**测量得到的星等称为**热星等，bolometric magnitude**，通常用 <img src="https://www.zhihu.com/equation?tex=m_{bol},M_{bol}" alt="m_{bol},M_{bol}" class="ee_img tr_noresize" eeimg="1"> 表示。

* ** <img src="https://www.zhihu.com/equation?tex=UBV" alt="UBV" class="ee_img tr_noresize" eeimg="1"> 波长滤色片，UBV Wavelength Filters**：恒星的颜色可以通过使用只在某些窄波段内允许传输星光的滤光片来精确确定。

  | 滤光片 | 星等     | 中心波长 <img src="https://www.zhihu.com/equation?tex=(nm)" alt="(nm)" class="ee_img tr_noresize" eeimg="1">  | 有效带宽 <img src="https://www.zhihu.com/equation?tex=(nm)" alt="(nm)" class="ee_img tr_noresize" eeimg="1">  |

  | ------ | -------- | -------------- | -------------- |

  | U      | 紫外星等 | 365            | 68             |

  | B      | 蓝色星等 | 440            | 98             |

  | V      | 目视星等 | 550            | 89             |


* **色指数和热改正，Color Indices and the Bolometric Correction**：

  不同星等的差值可以定义为**色指数**，

<img src="https://www.zhihu.com/equation?tex=U-B=M_U-M_B \\
  B-V=M_B-M_V
  " alt="U-B=M_U-M_B \\
  B-V=M_B-M_V
  " class="ee_img tr_noresize" eeimg="1">
  色指数 <img src="https://www.zhihu.com/equation?tex=B-V" alt="B-V" class="ee_img tr_noresize" eeimg="1"> 更小的恒星就比色指数 <img src="https://www.zhihu.com/equation?tex=B-V" alt="B-V" class="ee_img tr_noresize" eeimg="1"> 更大的恒星显得更蓝，其实可以理解为，蓝色星等与目视星等的“距离”小，观察看到的星光颜色也差距更小，显得更蓝。

  恒星的热星等与目视星等的差值就是**热改正**，

<img src="https://www.zhihu.com/equation?tex=BC=m_{bol}-V=M_{bol}-M_V
  " alt="BC=m_{bol}-V=M_{bol}-M_V
  " class="ee_img tr_noresize" eeimg="1">
  恒星的紫外星等可以用下式给出，

<img src="https://www.zhihu.com/equation?tex=U=-2.5\lg (\int_0^{\infty}F_\lambda S_Ud\lambda)+C_U
  " alt="U=-2.5\lg (\int_0^{\infty}F_\lambda S_Ud\lambda)+C_U
  " class="ee_img tr_noresize" eeimg="1">
  其中** <img src="https://www.zhihu.com/equation?tex=S" alt="S" class="ee_img tr_noresize" eeimg="1"> 是灵敏度函数**，描述在波长 <img src="https://www.zhihu.com/equation?tex=\lambda" alt="\lambda" class="ee_img tr_noresize" eeimg="1"> 处探测到的恒星的辐射流量部分。** <img src="https://www.zhihu.com/equation?tex=C_U" alt="C_U" class="ee_img tr_noresize" eeimg="1"> 是常数**，对于不同的滤光片， <img src="https://www.zhihu.com/equation?tex=C" alt="C" class="ee_img tr_noresize" eeimg="1"> 各不相同。一般是通过用这三个波段滤光片确定织女星（vega,天琴座 <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1"> ）的星等为零来确定这些常数。

  对于理想的辐射热计，可以探测到百分百的辐射，于是 <img src="https://www.zhihu.com/equation?tex=S(\lambda)\equiv1" alt="S(\lambda)\equiv1" class="ee_img tr_noresize" eeimg="1"> ，则有，

<img src="https://www.zhihu.com/equation?tex=m_{bol}=-2.5\lg (\int_0^{\infty}F_\lambda d\lambda)+C_{bol}
  " alt="m_{bol}=-2.5\lg (\int_0^{\infty}F_\lambda d\lambda)+C_{bol}
  " class="ee_img tr_noresize" eeimg="1">
  理想地， <img src="https://www.zhihu.com/equation?tex=BC=m_{bol}-V" alt="BC=m_{bol}-V" class="ee_img tr_noresize" eeimg="1"> 。由于恒星全波段辐射流量一定大于在任何特定波段上的辐射流量，所以**一般热改正值是负的**。不过某些超巨星有正的热改正。

* 双色图，the color-color diagram：显示主序星色指数 <img src="https://www.zhihu.com/equation?tex=U-B,B-V" alt="U-B,B-V" class="ee_img tr_noresize" eeimg="1"> 之间的关系。

  ![image-20240308210155595](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/光的连续谱/image-20240308210155595.png)

  虚线代表理想黑体模型的结果。

