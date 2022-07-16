# iechemistry

### 模型训练

yolov3模型训练在dl文件夹内，具体训练过程可通过下述链接查看。

https://github.com/tankWang1024/yolov3-pytorch-paper

### 前端微信小程序代码

微信小程序的前端代码。

https://github.com/tankWang1024/iechemistry-wechat

### 后端代码

此仓库为小程序后端代码。
智能化学平台,基于python flask的荧光实验分析处理平台

```
技术栈：
python 3.6 flask 1.1.2 flask-restful 0.3.8 PyJWT 2.0.1
pytorch 1.8.1 torchvision 0.9.1
opencv 3.4.2   scikit-learn 0.24.1
mysql 5.x
qiniu cos 七牛云对象存储
redis32
NVIDIA环境：cuda 10.2 CUDNN 8   开发硬件：GTX1050Ti 4GB
```

.qiniu_pythonsdk_hostscache中设置七牛云

config.py中设置数据库地址

## 智能化学平台 子模块

- 荧光分析
- 图像、数据的预处理
- 历史实验数据统计、分析
- 多种机器学习回归方法