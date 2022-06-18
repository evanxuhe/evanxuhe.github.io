# flink安装教程
[toc]


### 安装jdk
```bash

# 查询可用的openjdk
apt-cache search openjdk
# 安装jdk11和jre11
sudo apt install openjdk-11-jdk openjdk-11-jre
```
### 安装flink
```bash
# 使用阿里云镜像下载flink二进制 速度快
# --no-check-certificate是跳过认证
wget --no-check-certificate  https://mirrors.aliyun.com/apache/flink/flink-1.15.0/flink-1.15.0-bin-scala_2.12.tgz
```
[aliyun开源镜像站](https://mirrors.aliyun.com/apache/flink/flink-1.15.0/)
