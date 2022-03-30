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

# 4.原始实验的刺激
2声和3声刺激的起点都是184.9Hz，在0.2秒处出现转折，转折点的基频为138.6Hz，根据终点的基频高低，将3声条件分为low tone 3和high tone 3，将2声条件分为low tone 2和high tone 2。

![图5](../Supporting_Information/2021-06-20-XXM1-Fig-5.png)

![图6](../Supporting_Information/2021-06-20-XXM1-Fig-6.png)

根据原始实验刺激，制作了四种条件下“眼”和“岩”的语音。

刺激具体包括：
![图7](../Supporting_Information/2021-06-20-XXM1-Fig-7.png)
