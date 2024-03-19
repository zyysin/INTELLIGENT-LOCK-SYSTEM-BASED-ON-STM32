# 基于STM32的智能锁系统
## 系统功能简介
该设计采用STM32F103C8T6作为系统的主处理器，采用人脸识别、指纹识别以及密码判别三种方式进行用户的身份识别。在信息采集阶段，系统通过在K210处理器编写的YOLO算法进行人脸信息的目标检测，通过ATK-AS608指纹识别模块采集指纹信息，并采用矩阵键盘进行密码信息的采集工作。上述身份信息经过采集之后将实时传输到STM32F01处理器进行数据的处理与信息的比对，身份信息比对成功后系统方可开锁。
## 安装软件版本
KeiluVision5
Maix Py IDE
PZ-ISP
Kflash
