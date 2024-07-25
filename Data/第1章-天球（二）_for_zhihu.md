# 天球（二）

### 一，天球基本概念

#### 1. 天球的概念

**天球**就是**以观测者为中心，任意距离为半径的假想的球**。因此观测到的物体的位置其实是在天球上的投影。由于其半径的任意性，我们只考虑物体投影位置的**角距离**。

角度换算关系： <img src="https://www.zhihu.com/equation?tex=1\degree=60'=3600''" alt="1\degree=60'=3600''" class="ee_img tr_noresize" eeimg="1"> ,  <img src="https://www.zhihu.com/equation?tex=1 \text{rad}=57.3\degree" alt="1 \text{rad}=57.3\degree" class="ee_img tr_noresize" eeimg="1"> , 通常写为如下的形式： <img src="https://www.zhihu.com/equation?tex=120\degree30'30''.333" alt="120\degree30'30''.333" class="ee_img tr_noresize" eeimg="1"> 。

![几何法测距示意图](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725101336627.png)

#### 2. 天球上的基本点和圆

![天球示意图](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725103236138.png)

* **天顶 <img src="https://www.zhihu.com/equation?tex=Z" alt="Z" class="ee_img tr_noresize" eeimg="1"> 和天底 <img src="https://www.zhihu.com/equation?tex=Z'" alt="Z'" class="ee_img tr_noresize" eeimg="1"> （zenith，nadir）**：铅锤线与天球的交点，在观测者头顶的为天顶，反之为天底。
* **真地平圈（celestial horizon）**：垂直于天顶和天底连线、与天球相交的大圆。
* **天极（celestial pole）**：**北天极（ <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> ），南天极（ <img src="https://www.zhihu.com/equation?tex=P'" alt="P'" class="ee_img tr_noresize" eeimg="1"> ）**：地轴与天球的交点，指向北极的为北天极，反之为南天极。
* **天赤道（celestial equator）**：垂直于地轴，并与天球相交的大圆。
* **天子午圈（celestial meridian）**：过天极、天顶、天底的大圆。
* **四方点（cardinal points of horizon）**：**北点（ <img src="https://www.zhihu.com/equation?tex=N" alt="N" class="ee_img tr_noresize" eeimg="1"> ），南点（ <img src="https://www.zhihu.com/equation?tex=S" alt="S" class="ee_img tr_noresize" eeimg="1"> ）**：天子午圈与真地平的交点，其中靠近北天极的为北点，反之为南点；**东点（ <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> ），西点（ <img src="https://www.zhihu.com/equation?tex=W" alt="W" class="ee_img tr_noresize" eeimg="1"> ）**：天赤道与真地平的交点，根据南北点的方位判断东西点。
* **天卯酉圈（prime vertical）**：过东西点、天顶、天底的大圆。
* **黄道（ecliptic）**：与地球公转轨道平面平行的大圆。黄赤交角： <img src="https://www.zhihu.com/equation?tex=\varepsilon=23\degree27'" alt="\varepsilon=23\degree27'" class="ee_img tr_noresize" eeimg="1"> 。
* **黄极（ecliptic pole）**：**北黄极（ <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> ），南黄极（ <img src="https://www.zhihu.com/equation?tex=K'" alt="K'" class="ee_img tr_noresize" eeimg="1"> ）**：过观测者垂直于黄道的轴线与天球的交点。
* **二分二至点（equinoxes and solstices）**：**春分点，秋分点**：从北半球看，黄道按逆时针方向从天赤道南穿到天赤道北的升交点是春分点，降交点则是秋分点；**夏至点，冬至点**：黄道能到达的最高点和最低点分别为夏至点和冬至点。二分二至点所用的星座符号代表此时太阳所位于黄道上的位置。但1990年后，春分点移到了双鱼宫（双鱼座方向），但仍保留原来白羊座的符号。

### 二，常用的天球坐标系

#### 1. 一般的球面坐标系

![一般的球面坐标系](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725111822612.png)

* 坐标表示：**经度 <img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1"> **（第一坐标），**纬度 <img src="https://www.zhihu.com/equation?tex=v" alt="v" class="ee_img tr_noresize" eeimg="1"> **（第二坐标）

* **第一极**（基本方向），**基本圈**，**零点**（基本点）

* 球面坐标与直角坐标的转换：

<img src="https://www.zhihu.com/equation?tex=\begin{pmatrix}
  x \\
  y \\
  z
  \end{pmatrix}=
  \begin{pmatrix}
  \cos u\cos v \\
  \sin u \cos v \\
  \sin v
  \end{pmatrix}
  \tag{1}
  " alt="\begin{pmatrix}
  x \\
  y \\
  z
  \end{pmatrix}=
  \begin{pmatrix}
  \cos u\cos v \\
  \sin u \cos v \\
  \sin v
  \end{pmatrix}
  \tag{1}
  " class="ee_img tr_noresize" eeimg="1">

* **地理坐标**：第一、二极分别为北极和南极，基本圈是赤道圈，零经圈是格林尼治（本初）子午圈。

#### 2. 地平坐标系

![地平坐标系](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725112158346.png)

* 纬角：**高度 <img src="https://www.zhihu.com/equation?tex=h" alt="h" class="ee_img tr_noresize" eeimg="1"> **；余纬角：**天顶距 <img src="https://www.zhihu.com/equation?tex=z=90\degree-h" alt="z=90\degree-h" class="ee_img tr_noresize" eeimg="1"> **
* 经角：**方位角 <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> **（从北点向东/南点向西）
* **左旋**坐标系

#### 3. 时角坐标系（第一赤道坐标系）

![时角坐标系](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725112700612.png)

* 纬角：**赤纬** <img src="https://www.zhihu.com/equation?tex=\delta" alt="\delta" class="ee_img tr_noresize" eeimg="1"> ；赤纬余角：北极距 <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> 
* 经角：**时角** <img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1"> （**顺时针**，以**近南点的与赤道圈相交的点为零点**， <img src="https://www.zhihu.com/equation?tex=0^h\sim24^h" alt="0^h\sim24^h" class="ee_img tr_noresize" eeimg="1"> ）
* **左旋**坐标系
* 赤纬不变，**时角随时间变化具有地方性**

#### 4. 赤道坐标系（第二赤道坐标系）

![赤道坐标系](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725113123578.png)

* 纬角：**赤纬** <img src="https://www.zhihu.com/equation?tex=\delta" alt="\delta" class="ee_img tr_noresize" eeimg="1"> 
* 经角：**赤经** <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1"> （**逆时针**，零点是**春分点**， <img src="https://www.zhihu.com/equation?tex=0\sim360\degree" alt="0\sim360\degree" class="ee_img tr_noresize" eeimg="1"> ）
* **右旋**坐标系
* 引入了一个**和天球一起作周日旋转的点（春分点）作为零点**，于是天体的赤道坐标**与地球自转无关**

#### 5. 黄道坐标系

![黄道坐标系](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725113318625.png)

* 纬角：**黄纬** <img src="https://www.zhihu.com/equation?tex=\beta" alt="\beta" class="ee_img tr_noresize" eeimg="1"> 
* 经角：**黄经** <img src="https://www.zhihu.com/equation?tex=\lambda" alt="\lambda" class="ee_img tr_noresize" eeimg="1"> 
* **右旋**坐标系
* 黄道坐标不随观测时间和地点变化

#### 6. 银道坐标系

第一极是北银极，基本圈是银道，零点是银心方向

### 三，天球坐标的转换

#### 1. 球面三角法

<u>关键是要熟练掌握球面三角公式！</u>

![地平坐标与时角坐标的转换](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725114303002.png)

![赤道坐标与黄道坐标的转换](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725114308656.png)

#### 2. 旋转矩阵法

* 绕x，y，z轴的旋转矩阵（按照右手定则判断旋转方向）

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
  & R_x(\theta)=\begin{pmatrix}
  1 & 0 & 0 \\
  0 & \cos\theta & \sin\theta \\
  0 & -\sin\theta & \cos\theta
  \end{pmatrix} \\
  \\
  & R_y(\theta)=\begin{pmatrix}
  \cos\theta & 0 & -\sin\theta \\
  0 & 1 & 0 \\
  \sin\theta & 0 & \cos\theta
  \end{pmatrix} \\
  \\
  & R_z(\theta)=\begin{pmatrix}
  \cos\theta & \sin\theta & 0 \\
  -\sin\theta & \cos\theta & 0 \\
  0 & 0 & 1
  \end{pmatrix}
  \end{aligned}
  \tag{2}
  " alt="\begin{aligned}
  & R_x(\theta)=\begin{pmatrix}
  1 & 0 & 0 \\
  0 & \cos\theta & \sin\theta \\
  0 & -\sin\theta & \cos\theta
  \end{pmatrix} \\
  \\
  & R_y(\theta)=\begin{pmatrix}
  \cos\theta & 0 & -\sin\theta \\
  0 & 1 & 0 \\
  \sin\theta & 0 & \cos\theta
  \end{pmatrix} \\
  \\
  & R_z(\theta)=\begin{pmatrix}
  \cos\theta & \sin\theta & 0 \\
  -\sin\theta & \cos\theta & 0 \\
  0 & 0 & 1
  \end{pmatrix}
  \end{aligned}
  \tag{2}
  " class="ee_img tr_noresize" eeimg="1">

* 旋转矩阵性质：

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
  & R_k(\theta)R_k(\phi)=R_k(\theta+\phi) \\
  & R_k^n(\theta)=R_k(n\theta)\\
  & R_k^{-1}(\theta)=R_k(-\theta)=R_k^T(\theta)
  \end{aligned}
  \tag{3}
  " alt="\begin{aligned}
  & R_k(\theta)R_k(\phi)=R_k(\theta+\phi) \\
  & R_k^n(\theta)=R_k(n\theta)\\
  & R_k^{-1}(\theta)=R_k(-\theta)=R_k^T(\theta)
  \end{aligned}
  \tag{3}
  " class="ee_img tr_noresize" eeimg="1">

* 反向矩阵（用于变换左旋右旋）

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
  & P_x=\begin{pmatrix}
  -1 & 0 & 0 \\
  0 & 1 & 0 \\
  0 & 0 & 1
  \end{pmatrix} \\
  \\
  & P_y=\begin{pmatrix}
  1 & 0 & 0 \\
  0 & -1 & 0 \\
  0 & 0 & 1
  \end{pmatrix} \\
  \\
  & P_z=\begin{pmatrix}
  1 & 0 & 0 \\
  0 & 1 & 0 \\
  0 & 0 & -1
  \end{pmatrix}
  \end{aligned}
  \tag{4}
  " alt="\begin{aligned}
  & P_x=\begin{pmatrix}
  -1 & 0 & 0 \\
  0 & 1 & 0 \\
  0 & 0 & 1
  \end{pmatrix} \\
  \\
  & P_y=\begin{pmatrix}
  1 & 0 & 0 \\
  0 & -1 & 0 \\
  0 & 0 & 1
  \end{pmatrix} \\
  \\
  & P_z=\begin{pmatrix}
  1 & 0 & 0 \\
  0 & 1 & 0 \\
  0 & 0 & -1
  \end{pmatrix}
  \end{aligned}
  \tag{4}
  " class="ee_img tr_noresize" eeimg="1">

* ![地平坐标转换为时角坐标](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725120250760.png)

* ![时角坐标转换为赤道坐标](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725120316222.png)

* 注：写矩阵时，按顺序从右至左；计算矩阵时，自左向右。

### 四，天体的周日视运动

#### 1. 天球的周日旋转

天球上具有地方性的点和圈不动，例如天顶天底，四方点；天球上不具地方性的点和圈随天球旋转（南北天极除外），例如，赤道原地自东向西转动；春、秋分点依次经过东点、子午圈、西点；黄道绕地轴在摆动。

#### 2. 恒星的周日视运动

由于地球自转，导致天体在夜空中东升西落的视运动现象（因为地球自西向东自转，根据视运动相对性，看上去天体是在绕地球自东向西转动）。并且天体的运动平行于天赤道（因为地球绕地轴自转）。

#### 3. 不同纬度处天体的周日视运动

设 <img src="https://www.zhihu.com/equation?tex=\varphi" alt="\varphi" class="ee_img tr_noresize" eeimg="1"> 为天顶的赤纬。

* 极地（ <img src="https://www.zhihu.com/equation?tex=\varphi=90\degree" alt="\varphi=90\degree" class="ee_img tr_noresize" eeimg="1"> ）
  ![极地](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725133747828.png)

  所有天体的周日平行圈都与真地平平行。

* 赤道（ <img src="https://www.zhihu.com/equation?tex=\varphi=0\degree" alt="\varphi=0\degree" class="ee_img tr_noresize" eeimg="1"> ）
  ![赤道](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725133735785.png)
  所有天体的周日平行圈与真地平垂直。

* 一般地区

  ![一般地区](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725133858385.png)
  天赤道上的天体周日平行圈是大圆。

* 北极星（Polaris）：小熊座 <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1"> /勾陈一/北辰，与北极相距约1°。

* 拱极星（Circumpolar star）：恒星永远都不会落入地平线以下。因此在不同的地理纬度处，拱极星不同。

#### 4. 与周日视运动相关的现象

* 出（rise）、没（set）：天体在分别在东边和西边与真地平的交点处，此时天顶距为90°。

* 上中天（upper culmination）、下中天（lower culmination）：天体通过观测地的子午圈叫做天体的中天。在北天极以南中天叫做上中天，此时天体到达最高位置；在北天极以北中天叫做下中天，此时天体到达最低位置。
  白夜：夏至前后，夜晚太阳到达下中天位置时，依然停留在地平线上方；
  黑昼：冬至前后，白天太阳到达上中天位置时，依然停留在地平线下方；
  出现白夜和黑昼的地方在地球的南北极圈内。

* 天体过卯酉圈：天体的周日平行圈与卯酉圈相交。

* 天体过大距：
  ![天体过大距](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725135131021.png)

  星位角：天体的赤经圈（图中的 <img src="https://www.zhihu.com/equation?tex=P\sigma'P'" alt="P\sigma'P'" class="ee_img tr_noresize" eeimg="1"> ）与地平经圈（图中的 <img src="https://www.zhihu.com/equation?tex=Z\sigma'Z'" alt="Z\sigma'Z'" class="ee_img tr_noresize" eeimg="1"> ）在天体 <img src="https://www.zhihu.com/equation?tex=\sigma'" alt="\sigma'" class="ee_img tr_noresize" eeimg="1"> 处的夹角称为星位角。

  当天体 <img src="https://www.zhihu.com/equation?tex=|\delta|>\varphi" alt="|\delta|>\varphi" class="ee_img tr_noresize" eeimg="1"> 时，其周日平行圈不与卯酉圈相交。当地平经圈与周日平行圈相切时/或星位角为90°时，天体过这两切点的位置分别为东、西大距。

### 五，星空周年变化和太阳周年视运动

#### 1. 恒星日和太阳日

![恒星日和太阳日](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725142500620.png)

恒星日：地球相对于远处恒星自转一周的时间具体来说，就是地球旋转360度所需的时间。大约是 <img src="https://www.zhihu.com/equation?tex=23^h56'4''" alt="23^h56'4''" class="ee_img tr_noresize" eeimg="1"> 。

太阳日：地球相对于太阳自转一周的时间，使得太阳连续两天出现在同一位置所经历的时间。大约是 <img src="https://www.zhihu.com/equation?tex=24^h" alt="24^h" class="ee_img tr_noresize" eeimg="1"> 。

太阳日之所以比恒星日长，是因为地球在自转的同时也在绕太阳公转。因此地球自转一周后，要额外旋转一点角度之后才能使太阳回到同一位置。该角度即 <img src="https://www.zhihu.com/equation?tex=\frac{360}{365}\approx1\degree" alt="\frac{360}{365}\approx1\degree" class="ee_img tr_noresize" eeimg="1"> 。

#### 2. 黄道十二宫

以太阳为中心，地球环绕太阳所经过的轨迹称为**黄道**。其宽约18°，环绕地球360°，每30°为一段，称为黄道十二宫。

黄道十二宫表示太阳在黄道上的位置。黄道附近的星座宽度不一，但宫的大小均为30°。太阳进入每一宫的时间基本固定。

#### 3. 季节的变化

日长、太阳入射角等联合作用，<u>并非日地距离的变化引起！</u>

**黄赤交角**：23.5°；黄道相对于赤道的**升交点为春分点**；**降交点为秋分点**；**最高点为夏至点**；**最低点为冬至点**。

**回归年**：地球连续两次经过**春分点**的时间间隔。

#### 4. 太阳的视运动

即平行于**赤道**面顺时针方向的**周日视运动**以及沿**黄道**做逆时针方向的**周年视运动**。

#### 5. 星空的周年变化

地球绕太阳公转，导致夜晚星空的季节性变化。

（不同季节星空的介绍：[四季星空 | 香港太空馆 (space.museum)](https://hk.space.museum/sc/web/spm/resources/teachers-corner/starry-sky-of-the-four-seasons.html)）

### 六，时间及其计量

#### 1. 时间计量与时间标准

时间计量需要以观测物体的运动为基础；作为计量标准的物体运动要求具有**均匀性**，**连续性**，**可测性**和**周期性**。

天文时间系统包括：

* 以地球自转为基础：**太阳时，恒星时**；统称为世界时（UT），其秒长不固定，但是容易测量。
* 以太阳系内天体公转为基础：**历书时**（ET）。
* 以原子内部能级跃迁频率为标准：**原子时**（TAI）。其秒长固定，测量容易，是一种物理时；前两者称为天文时。

#### 2. 世界时系统

* **恒星时**（Sidereal time）
  **春分点**连续两次上中天的时间间隔为1个**恒星日**。恒星时起点为春分点上中天，恒星时是不均匀的。
  天文学中，观测时刻需要以恒星时计量。

<img src="https://www.zhihu.com/equation?tex=s=t+\alpha,\quad s=t_\Upsilon
  \tag{5}
  " alt="s=t+\alpha,\quad s=t_\Upsilon
  \tag{5}
  " class="ee_img tr_noresize" eeimg="1">
  其中 <img src="https://www.zhihu.com/equation?tex=t_\Upsilon" alt="t_\Upsilon" class="ee_img tr_noresize" eeimg="1"> 为春分点的时角。

* **真太阳时**（Apparent solar time）
  **真太阳视圆面中心**连续两次上中天的时间间隔为1**真太阳日**。
  1真太阳日=24真太阳时。
  将真太阳时起点定为其下中天时刻，故有

<img src="https://www.zhihu.com/equation?tex=M_\odot=t_\odot+12^h
  \tag{6}
  " alt="M_\odot=t_\odot+12^h
  \tag{6}
  " class="ee_img tr_noresize" eeimg="1">
  其不均匀，但与日常生活节律一致。

* **平太阳时**（Mean solar time）
  引入假想的数学点：**平太阳**。第一辅助点：黄道平太阳，在黄道上做匀速运动，其视运动的速度为真太阳视运动速度的平均值，且与真太阳同时经过近、远日点。第二辅助点：赤道平太阳，在赤道上做匀速运动，与第一辅助点速度相同，且两者同时经过春、秋分点。
  简称平时，**格林尼治的平时称为世界时**。
  赤道平太阳连续两次上中天的时间间隔为1平太阳日，实际采用下中天为起点。

<img src="https://www.zhihu.com/equation?tex=m=t_m+12^h
  \tag{7}
  " alt="m=t_m+12^h
  \tag{7}
  " class="ee_img tr_noresize" eeimg="1">
  其完全反应了地球自转速率，基本均匀，且与日常生活的节奏一致。

* 太阳日与恒星日关系：
  ![太阳日与恒星日关系](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725173616466.png)

### 七，不同时间计量单位系统的换算

#### 1. 真太阳时与平时换算

令**真、平太阳时**的差值为时差 <img src="https://www.zhihu.com/equation?tex=\eta" alt="\eta" class="ee_img tr_noresize" eeimg="1"> ，则有

<img src="https://www.zhihu.com/equation?tex=\eta = t_\odot-t_m=m_\odot-m
\tag{8}
" alt="\eta = t_\odot-t_m=m_\odot-m
\tag{8}
" class="ee_img tr_noresize" eeimg="1">
 <img src="https://www.zhihu.com/equation?tex=t_\odot" alt="t_\odot" class="ee_img tr_noresize" eeimg="1"> ：真太阳时的时角， <img src="https://www.zhihu.com/equation?tex=t_m" alt="t_m" class="ee_img tr_noresize" eeimg="1"> ：平时的时角； <img src="https://www.zhihu.com/equation?tex=m_\odot" alt="m_\odot" class="ee_img tr_noresize" eeimg="1"> ：真太阳时， <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> ：平时

#### 2. 世界时，地方时和区时

* 不同地点的**地方平时**：

<img src="https://www.zhihu.com/equation?tex=m_B-m_A=\lambda_B-\lambda_A=\Delta \lambda \quad \text{(平时单位)}
  \tag{9}
  " alt="m_B-m_A=\lambda_B-\lambda_A=\Delta \lambda \quad \text{(平时单位)}
  \tag{9}
  " class="ee_img tr_noresize" eeimg="1">
  注意区分**时分秒**单位和**度分秒**单位： <img src="https://www.zhihu.com/equation?tex=1^h=15\degree,1^m=15',1^s=15'',1\degree=4^m,1'=4^s" alt="1^h=15\degree,1^m=15',1^s=15'',1\degree=4^m,1'=4^s" class="ee_img tr_noresize" eeimg="1"> 。

* 不同地方的恒星时：

<img src="https://www.zhihu.com/equation?tex=s_B-s_A=\lambda_B-\lambda_A=\Delta \lambda\quad \text{(恒星时单位)}
  \tag{10}
  " alt="s_B-s_A=\lambda_B-\lambda_A=\Delta \lambda\quad \text{(恒星时单位)}
  \tag{10}
  " class="ee_img tr_noresize" eeimg="1">

* 时区和区时：
  在同一时区内，采用中央经线上的地方平时。**零时区区时**，即**格林尼治地方平时**，即**世界时**。

* 日界线：180°经线，即国际日期变更线。日界线西侧到东侧，日期减一天，反之加一天。

* 地方平时与区时换算，N代表第N时区， <img src="https://www.zhihu.com/equation?tex=T_N" alt="T_N" class="ee_img tr_noresize" eeimg="1"> 为区时：

<img src="https://www.zhihu.com/equation?tex=m=T_N+(\lambda-N^h)=(T_N-N^h)+\lambda
  \tag{11}
  " alt="m=T_N+(\lambda-N^h)=(T_N-N^h)+\lambda
  \tag{11}
  " class="ee_img tr_noresize" eeimg="1">

#### 3. 恒星时与平时

1回归年=366.2422恒星日=365.2422平太阳日

1恒星时单位=(1- <img src="https://www.zhihu.com/equation?tex=\nu" alt="\nu" class="ee_img tr_noresize" eeimg="1"> )平时单位

1平时单位=(1+ <img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> )恒星时单位

 <img src="https://www.zhihu.com/equation?tex=\mu=\frac{1}{365.2422}=2.737909\times 10^{-3}" alt="\mu=\frac{1}{365.2422}=2.737909\times 10^{-3}" class="ee_img tr_noresize" eeimg="1"> 

 <img src="https://www.zhihu.com/equation?tex=\nu=\frac{1}{366.2422}=2.730434\times 10^{-3}" alt="\nu=\frac{1}{366.2422}=2.730434\times 10^{-3}" class="ee_img tr_noresize" eeimg="1"> 

设 <img src="https://www.zhihu.com/equation?tex=S" alt="S" class="ee_img tr_noresize" eeimg="1"> 为格林尼治恒星时， <img src="https://www.zhihu.com/equation?tex=S_0" alt="S_0" class="ee_img tr_noresize" eeimg="1"> 为世界时零时恒星时， <img src="https://www.zhihu.com/equation?tex=s" alt="s" class="ee_img tr_noresize" eeimg="1"> 为地方恒星时， <img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1"> 为格林尼治现在平时， <img src="https://www.zhihu.com/equation?tex=M_0" alt="M_0" class="ee_img tr_noresize" eeimg="1"> 为格林尼治恒星时零时世界时， <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> 为地方平时。

* 已知地方平时求地方恒星时：

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
  s & \equiv S+\lambda \\
  & = S_0+M(1+\mu)+\lambda \\
  & =S_0+(m-\lambda)(1+\mu)+\lambda \\
  & =S_0+m+(m-\lambda)\mu
  \end{aligned}
  \tag{12}
  " alt="\begin{aligned}
  s & \equiv S+\lambda \\
  & = S_0+M(1+\mu)+\lambda \\
  & =S_0+(m-\lambda)(1+\mu)+\lambda \\
  & =S_0+m+(m-\lambda)\mu
  \end{aligned}
  \tag{12}
  " class="ee_img tr_noresize" eeimg="1">

* 已知地方恒星时求地方平时：

<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
  m & \equiv M+\lambda \\
  & = M_0+S(1-\nu)+\lambda \\
  & =M_0+(s-\lambda)(1-\nu)+\lambda \\
  & =M_0+s-(s-\lambda)\mu
  \end{aligned}
  \tag{13}
  " alt="\begin{aligned}
  m & \equiv M+\lambda \\
  & = M_0+S(1-\nu)+\lambda \\
  & =M_0+(s-\lambda)(1-\nu)+\lambda \\
  & =M_0+s-(s-\lambda)\mu
  \end{aligned}
  \tag{13}
  " class="ee_img tr_noresize" eeimg="1">

时间轴可以辅助换算：
![时间轴](https://raw.githubusercontent.com/Daihuoo/Markdown4Zhihu/master/Data/第1章-天球（二）/image-20240725184201880.png)