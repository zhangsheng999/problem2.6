# problem2.6
### 题目大意
忽略空气阻力和空气密度的影响，使用欧拉方法计算炮弹飞行的轨迹线，并将你的结果和Figure2.4比较
### 解答
我们首先定义一个类class flight_state，里面可以储存任意时刻的水平位置x,垂直位置y，水平速度vx，垂直速度vy以及时刻t
参考教材，有

![](https://github.com/zhaozhanyi0804/computationalphysics_N2015301020052/blob/master/Homework_5/5-3.jpg)
 
 考虑到方程没有解析解，于是根据欧拉法递推确定下一时刻的飞行状态，直到y小于等于0。dt设为0.1。
此时我们将初速度给定为700米每秒，然后不断调整发射角度得到一下图像
#### θ=30°
得到图像
![]（https://github.com/zhangsheng999/1111/blob/master/1.png）
