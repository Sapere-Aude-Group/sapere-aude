---
title: 用praat中的PSOLA算法改变基频
author: 夏秀媚
date: 2021-06-20
showDate: true
showTOC: true
---
# 1.用讯飞合成的1声的“书”（shu）
![图1](../Supporting_Information/2021-06-20-XXM1-Fig-1.png)

通过F0曲线可以看出，即使是1声的刺激，其F0也有些弯曲。以下的F0变化均基于“书”（shu）这个刺激。

# 2.改变终点基频，使声调变得完全平直
![图2](../Supporting_Information/2021-06-20-XXM1-Fig-2.png)

使终点基频值等于起点基频值，中间各点的基频值会根据PSOLA算法自动生成。

# 3.改变终点基频，使声调变成rising tone

![图3](../Supporting_Information/2021-06-20-XXM1-Fig-3.png)

（1）终点基频值上升10Hz,使用平直的直线去拟合中间的F0。

![图4](../Supporting_Information/2021-06-20-XXM1-Fig-4.png)

（2）终点基频值上升20Hz，使用光滑的曲线去拟合中间的F0，使用这种方法生成的语音更自然。
