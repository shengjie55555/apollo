﻿# 概览

自动驾驶系统集车辆学、人工智能、计算机科学、自动控制等多学科应用于一体，是一个非常复杂的系统。而要搭建一个闭环的自动驾驶系统，不仅技术门槛高，还面临着资金成本高、政策约束等多方面的挑战。 Apollo开源平台的出现，极大的降低了学习自动驾驶的技术门槛； 而Apollo开发套件的出现，又进一步降低了搭建闭环自动驾驶系统所涉及到的车辆硬件成本高、采购周期长、测试场地限制等等各种成本。 该用户手册旨在帮助用户通过Apollo开发套件学习并使用Apollo自动驾驶平台。

手册覆盖了Apollo开发套件的一个使用场景，循迹自动驾驶场景。循迹自动驾驶指让车辆按照录制好的轨迹线进行自动驾驶，其涉及到自动驾驶中最基本的底盘线控能力、定位能力、控制能力，是自动驾驶系统的一个最小子集。

## 内容
**循迹自动驾驶搭建**
- [循迹搭建--Apollo系统安装](Waypoint_following--Apollo_software_installation_cn.md)
- [循迹搭建--车辆集成](Waypoint_following--Vehicle_integration_cn.md)
- [循迹搭建--定位模块配置](Waypoint_following--Localization_configuration_cn.md)
- [循迹搭建--车辆动力学标定](Waypoint_following--Vehicle_calibration_cn.md)
- [循迹搭建--车辆循迹演示及常见问题](Waypoint_following--Operation_and_questions_cn.md)

## 循迹搭建--Apollo系统安装
在集成车辆之前，首先需要在工控机上完成Apollo系统的软硬件安装，如CAN卡安装；之后需要完成工控机的软件安装，包括Ubuntu Linux安装、Apollo软件系统安装等。

## 循迹搭建--车辆集成
在车辆集成环节，将完成工控机、路由器、惯导、显示器等设备在车辆上的集成。

## 循迹搭建--定位模块配置
定位模块的配置与验证。

## 循迹搭建--车辆动力学标定
本环节将介绍生成车辆动力学标定表的工具和方法，形成控制闭环以获得更好的控制效果。

## 循迹搭建--车辆循迹演示及常见问题
在完成以上软硬件安装，标定以及系统文件配置后，用户可以通过Dreamview界面录制车辆轨迹并回放，完成第一个循迹演示。
油门刹车标定是车辆纵向精准控制的前提。用户可以使用系统预先标定好的参数，也可以按照手册说明重新进行标定以获得更好的控制效果。

