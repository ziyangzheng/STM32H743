# STM32H743 伞兵三号飞控
学生维护不易，如果觉得有帮助还请点星星支持一下，感谢。



基于STM32H7芯片，CUBEMX平台，CLION编辑器，内嵌FreeRTOS系统的飞控项目。



**2021/8/7** : 开发飞控。刚起步阶段。

​					目前构思是分为四层：

​					1，APP_layer 			   ——用户上层											

​					2，Compute_layer	  ——飞行解算层											

​					3，System_layer  		——系统层											

​					4，Hardware_layer 	——底层与芯片相关的驱动层											

**2021/8/10**：

+ 首次更新底层PWM，ppm，I2C，RGB。
+ 上传原理图，引脚配置



**2021/8/27：**

+ 添加FreeRTOS系统，创建主程序。
+ 添加IMU读取以及相关滤波。
+ 添加姿态解算功能，采用的是Madgwick作者的梯度下降姿态融合算法。
+ 添加遥控器解析，解锁上锁识别功能。



**代办事务**：

+ SPI
+ ultrasonic

