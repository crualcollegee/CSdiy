### 前置准备：下载python，添加环境变量，安装pytorch

# lecture1

#### ·计算机视觉与机器学习的相互促进

#### 困难

机器看到的图片是二维矩阵，较难分析

从不同角度拍摄的图片对应的矩阵可能差异较大

有遮挡

部分照光

运动导致的模糊

#### 计算机视觉的历史

1970 shape from shading :recover 3d from aa single 2d

1978:intrinsic images :decomposing an image into its different

1980 :  获得三个不同光线照射下的图像，可以绘制每一点的法线

1981 从稍微不同的位置拍摄两张图片，类似人眼，获取3d

1981 获取动态图，方向与运动速度（用长度表示）

<img src="C:\Users\陈皓天\AppData\Roaming\Typora\typora-user-images\image-20240630103241054.png" alt="image-20240630103241054" style="zoom:67%;" />

1986，1988 在自动驾驶中的应用

2014     微小的干扰，使得机器将三个识别成鸵鸟

<img src="C:\Users\陈皓天\AppData\Roaming\Typora\typora-user-images\image-20240630105528671.png" alt="image-20240630105528671" style="zoom:67%;" />

<img src="C:\Users\陈皓天\AppData\Roaming\Typora\typora-user-images\image-20240630105941485.png" alt="image-20240630105941485" style="zoom:67%;" />

3D scanning  

2016  style transfer 将显示照片和其他图片结合，改变原图像风格

​    https://deepart.io/

2017 输入图像，输出对它的语言描述，但仍然缺乏理解

2018 人类动作分析

2016-2020 3D深度学习