##  HuaiA_003_开关量输入模块


### 01 功能作用及支持模块

&emsp;&emsp;将外部开关量传感器的状态信息输入给Spike的力传感器！
&emsp;&emsp;支持的开关量模块有（目前以YFrobot为主）：
    
    1.按键模块
    2.触摸模块
    3.震动模块
    4.热释电模块 
    5.磁控开关
    6.角度模块
    7.红外感应模块
    8.碰撞检测
    
&emsp;&emsp;实际上可以支持市面上几乎所有的SVG类型的开关量输入模块，只需要使用者根据接口接线就可以。


### 02 使用方法

#### 02-1 硬件连接
&emsp;&emsp;转接模块上有 **The Powered Up connector**接口直接和Hub连接；转接模块侧面有PH2.00-4P接口直接和开关量传感器连接即可。

#### 02-2 软件编程

&emsp;&emsp;编程软件目前测试使用乐高官方的 **LEGO Education SPIKE-2.0.1**和 **LEGO Mindstorms Robot Inventor 10.3.0**版本。

&emsp;&emsp;此开关量输入模块 **数据传输** 模拟的是力传感器（The Force Sensor），所以功能同Spike的力传感器（The Force Sensor）一样。力传感器对应的数值与模拟值对应如下：

1. 压力值--->对应数值0~1
2. 牛顿值--->对应数值0~10
3. 数  值--->对应数值0~4095


&emsp;&emsp;编程软件自带的模式支持如下：

1. 支持图标模式（待测试）
2. 支持词语模式
3. Python模式（待测试，理论上应该也是可以的）

#### 02-3 编程模块使用

同力传感器使用方法一样。

### 03 案例参考

#### 03-1 外接按键模块

##### 03-1-1 功能介绍

##### 03-1-2 软件编程


### 03-2 外接触摸模块
### 03-3 外接震动模块
### 03-4 外接热释电模块
### 03-5 外接磁控开关
### 03-6 外接角度模块
### 03-7 外接红外感应模块
### 03-8 外接碰撞检测

