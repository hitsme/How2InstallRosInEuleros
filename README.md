<div align="center">  

<img src="http://my-blog-to-use.oss-cn-beijing.aliyuncs.com/18-11-16/49833984.jpg" width=""/>
</br>

</div>



## 目录

- [:coffee: Java](#coffee-java)
  - [Java/J2EE 基础](#javaj2ee-基础)
  - [Java 集合框架](#java-集合框架)
  - [Java 多线程](#java-多线程)
  - [Java IO 与 NIO](#java-io-与-nio)
  - [Java 虚拟机 jvm](#java-虚拟机-jvm)
- [:open_file_folder: 数据结构与算法](#open_file_folder-数据结构与算法)
  - [数据结构](#数据结构)
  - [算法](#算法)
- [:computer: 计算机网络与数据通信](#computer-计算机网络与数据通信)
  - [网络相关](#网络相关)
  - [数据通信\(RESTful、RPC、消息队列\)](#数据通信restfulrpc消息队列)
- [:iphone: 操作系统](#iphone-操作系统)
  - [Linux相关](#linux相关)
- [:pencil2: 主流框架/软件](#pencil2-主流框架软件)
  - [Spring](#spring)
  - [ZooKeeper](#zookeeper)
- [:floppy_disk: 数据存储](#floppy_disk-数据存储)
  - [MySQL](#mysql)
  - [Redis](#redis)
- [:punch: 架构](#punch-架构)
  - [分布式相关](#分布式相关)
- [:musical_note: 面试必备](#musical_note-面试必备)
  - [备战春招/秋招系列](#备战春招秋招系列)
  - [最最最常见的Java面试题总结](#最最最常见的java面试题总结)
- [:art: 闲谈](#art-闲谈)
- [:envelope: 说明](#envelope-说明)
  - [项目介绍](#项目介绍)
  - [关于转载](#关于转载)
  - [如何对该开源文档进行贡献](#如何对该开源文档进行贡献)
  - [为什么要做这个开源文档？](#为什么要做这个开源文档)
  - [最后](#最后)
  - [福利](#福利)
  - [公众号](#公众号)
  

1.环境准备
cmake https://cmake.org/download/
yum install gcc gcc-c++
gcc https://blog.csdn.net/qq_33571814/article/details/82380215
Cmake3.17.2(下载二进制安装包)
pip install -U rosdep rosinstall_generator wstool rosinstall
Pip install empy
/etc/issue

编译安装boost(https://www.cnblogs.com/smallredness/p/9245127.html)

2.rosdep init
 rosdep update
替换以下文件为centos 7内容，跳过rosdep update对系统的match
/etc/os-release
/etc/redhat-release
/usr/lib/os-release

3.http://wiki.ros.org/console_bridge
4.yum -y install bzip2
 git clone -b master https://github.com/pocoproject/poco.git
