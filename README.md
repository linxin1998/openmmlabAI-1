# openmmlabAI-1
openmmlab实战营第一次作业
https://mmclassification.readthedocs.io/en/latest/
实验基于ImageNet-1k作为pretrained进行finetuned [预训练权值下载]（https://github.com/open-mmlab/mmclassification）
# 基础实验
使用mmclassification对花进行分类
# 实验设备
NVIDIA GeForce GTX 3090
# flower数据集
flower 数据集包含 5 种类别的花卉图像：雏菊 daisy 588张，蒲公英 dandelion 556张，玫瑰 rose 583张，向日葵 sunflower 536张，郁金香 tulip 585张。

数据集下载链接：
国际网：https://www.dropbox.com/s/snom6v4zfky0flx/flower_dataset.zip?dl=0

使用resnet50作为backbone的模型训练文件，放在百度网盘中。链接：https://pan.baidu.com/s/1GbmY8VzCRLV_rqeNXRZg_g 
提取码：vloe
最后一个epoch：accuracy_top-1: 94.4056%, accuracy_top-5: 100.0000&

# 进阶实验
使用mmclassification对CIFAR-10进行分类
图像分类数据集：CIFAR-10：https://opendatalab.com/CIFAR-10 562M
使用resnet50作为backbone的模型训练文件，放在百度网盘中。链接：https://pan.baidu.com/s/1lnIElnwwM-oRp_TgkCuFNw 
提取码：tovq
最后一个epoch：accuracy_top-1: 82.7200%, accuracy_top-5: 99.1100%

