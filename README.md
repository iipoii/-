# Digital-image-processing
# 这里是数字图像处理课程的作业
#### 1. ex1作业题目:对一张灰度图片进行线性、分段线性、非线性的点运算，对比原图和进行灰度变化后的效果
使用包如下
```
import matplotlib.pyplot as plt
import cv2 as cv
import numpy as np
```
代码使用```cv.imread()```函数读取灰度图像,保存为一个```ndarray```数组,数组元素为0~255的灰度值,在此基础上对灰度进行运算。计算完成后.使用```plt.imshow()```函数显示运算后的灰度图像,与原图进行对比。
