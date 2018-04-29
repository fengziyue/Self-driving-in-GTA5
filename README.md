# Self-driving-in-GTA5
Using Alex_Net to implement self-driving in GTA5

[<iframe width="560" height="315" src="https://www.youtube.com/embed/kEqNOkhJBT8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>]
[![Alt text for your video](https://img.youtube.com/vi/kEqNOkhJBT8/0.jpg)](http://www.youtube.com/watch?v=kEqNOkhJBT8)

## Requirements:
numpy
pandas
tensorflow
opencv-python
pypiwin32
tflearn

## 大致思路
将GTA5 以800x600 分辨率窗口模式运行，放在桌面左上角。用键盘控制车辆行驶，程序将记录下游戏画面和玩家按键。图片经过处理后以“左按键”或“右按键”作为标签送入Alex Net训练。
测试时将游戏画面送入Alex Net进行分类，根据分类结果自动生成按键信号，实现自动驾驶。

## 参考资料
https://www.youtube.com/watch?v=ks4MPfMq8aQ&list=PLQVvvaa0QuDeETZEOy4VdocT7TOjfSA8a
