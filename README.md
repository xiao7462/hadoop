# hadoop 学习笔记
* [视频](https://www.bilibili.com/video/av32081351/?p=19)
* [手册](http://hadoop.apache.org/docs/r1.0.4/cn/quickstart.html)
# 目录
-[安装，环境配置](#安装，环境配置)    

# 安装，环境配置   
* JDK 下载地址  https://pan.baidu.com/s/1piply8oOjVv_La3z17Hcwg       
  hadoop下载地址 https://www-eu.apache.org/dist/hadoop/common/hadoop-3.1.2/hadoop-3.1.2.tar.gz  
* 配置 
  下载完成后 `tar zxvf` 解压相应的包，
  配置环境变量  `vim ~/.bashrc`
  ```bash
  # JAVA_HOME
  export JAVA_HOME = ...  # jdk安装目录
  export PATH=$PATH:$JAVA_HOME/bin
  
  # HADOOP_HOME
  export HADOOP_HOME = ... # hadopp安装目录
  export PATH=$PATH:$HADOOP_HOME/bin
  export PATH=$PATH:$HADOOP_HOME/sbin
  ```
  再 `source ~/.bashrc`
