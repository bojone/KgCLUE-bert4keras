# KgCLUE-bert4keras
基于“Seq2Seq+前缀树”的知识图谱问答

## 简介
- 博客：https://kexue.fm/archives/8802

<img src="https://kexue.fm/usr/uploads/2021/12/1364258025.png" width=560>

## 环境
- 软件：bert4keras>=0.10.8
- 硬件：目前的结果是用一张Titan RTX（24G）跑出来的。

## 运行
- 第一次运行的时候，会给知识库构建前缀树，然后保存下来，这个过程大概需要30分钟左右；
- 如果是第二次运行，那么就会自动加载保存好的前缀树，这个过程大概需要5分钟左右；
- 保存下载的前缀树文件大概1.8G，加载到运行环境中，大概需要30G内存；
- 每个epoch的训练时间是很快的，反而是验证效果时间比较长，跑完训练和测试，大概需要1～2小时。

## 交流
QQ交流群：808623966，微信群请加机器人微信号spaces_ac_cn
