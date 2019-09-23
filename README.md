# RFSong-779进行行人检测
重新设计的RFBNet300,模型参数量只有0.99MB，AP达到0.78，速度可以达到200FPS

文章链接：https://zhuanlan.zhihu.com/p/76491446

## 环境
在python3.6 Ubuntu16.04 pytorch1.1下进行了实验
- 编译NMS

 `./make.sh`

# 与RFB不同的是
- 代码更方便进行自己设计网络
- 网络非常轻量级只有0.99 MB
- 网络速度相比RFB有显著提升,能够达到200FPS

欢迎加群交流，云深不知处-目标检测 763679865
