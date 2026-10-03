# YOLOv8目标检测项目实验报告
学号：202611160534
姓名：刘翔宇

## 一、实验概述
本项目使用YOLOv8模型完成多类别目标检测，分为5个Level逐步完成：环境搭建、数据集制作、模型训练、模型评估、可视化页面部署。

## Level1 环境搭建
搭建Ubuntu虚拟机环境，安装PyTorch、YOLOv8依赖库，完成基础推理测试，验证环境可用性。
![level1图1](images/picture.level1/level1.1.png)
![level1图2](images/picture.level1/level1.2.png)
## Level2 数据集制作
采集435张图像，使用LabelImg工具进行标注，生成YOLO格式txt标签文件。按照9:1划分数据集，训练集391张，验证集44张。
![level2图1](images/picture.level2/level2.1.png)
![level2图2](images/picture.level2/level2.2.png)
![level2图3](images/picture.level2/level2.3.png)
![level2图4](images/picture.level2/level2.4.png)
## Level3 模型训练
使用自制数据集训练YOLOv8模型，查看训练损失、精度指标。
![level3图1](images/picture.level3/20261002-102102.png)
![level3图2](images/picture.level3/屏幕截图%202026-10-02%20103242.png)
![level3图3](images/picture.level3/屏幕截图%202026-10-02%20103333.png)
![level3图4](images/picture.level3/屏幕截图%202026-10-02%20103725.png)
![level3图5](images/picture.level3/屏幕截图%202026-10-02%20103932.png)

## Level4 新图检测
使用自己训练得到的模型，对训练集之外的新图片进行目标检测。
![level4图1](images/picture.level4/屏幕截图%202026-10-02%20104311.png)
![level4图2](images/picture.level4/屏幕截图%202026-10-02%20104537.png)

## Level5 制作页面
在完成模型训练和新图片推理后，可以进一步将模型封装成一个简单的本地可视化应用。
![level5图1](images/picture.level5/屏幕截图%202026-10-02%20111529.png)
