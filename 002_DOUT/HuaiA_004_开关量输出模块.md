##  HuaiA_004_开关量输出模块


### 01 功能作用及支持模块

&emsp;&emsp;利用超声波传感器的亮灯功能输出高低电平控制外部传感器模块！
&emsp;&emsp;支持的模块有（目前以YFrobot为主）：
    
    1.食人鱼模块（红绿灯）
    2.继电器模块
    3.风扇模块
    4.振动模块 
    5.蜂鸣器

&emsp;&emsp;实际上可以支持市面上几乎所有的SVG类型的控制模块，只需要使用者根据接口接线就可以。


### 02 使用方法

#### 02-1 硬件连接
&emsp;&emsp;转接模块上有 **The Powered Up connector**接口直接和Hub连接；转接模块侧面有PH2.00-4P接口直接和开关量输出模块连接即可。

#### 02-2 软件编程

&emsp;&emsp;编程软件目前测试使用乐高官方的 **LEGO Education SPIKE-2.0.1**和 **LEGO Mindstorms Robot Inventor 10.3.0**版本。

&emsp;&emsp;此开关量输出模块 **数据传输** 模拟的是超声波传感器（the distance sensor），所以功能同Spike的超声波传感器the distance sensor）一样。

&emsp;&emsp;此模块的输出控制方式同超声波传感器亮灯控制一样，对应如下：

1. 点亮任何一个灯--->输出高电平
2. 所有灯全灭    --->输出低电平


&emsp;&emsp;编程软件自带的模式支持如下：

1. 支持图标模式（待测试）
2. 支持词语模式
3. Python模式（待测试，理论上应该也是可以的）



### 03 案例参考

#### 03-1 食人鱼模块（红绿灯）

##### 03-1-1 功能介绍

##### 03-1-2 软件编程


### 03-2 继电器模
### 03-3 风扇模块
### 03-4 振动模块 
### 03-5 蜂鸣器

