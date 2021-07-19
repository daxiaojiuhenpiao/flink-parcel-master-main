源码来自https://github.com/EvenGui/flink-parcel-master
本人替换换了部分源改为国内的源，修改小部分代码，方便编译。

#进入项目目录
cd flink-parcel-master

#编译parcel包
./build.sh parcel

#编译parcel包
./build.sh csd

# 集成目的

- 集成Flink HistoryServer至CDH（在CDH上运行的Flink程序，在程序结束后的任务均会显示在该角色实例的WebUI上）
- 集成Gateway（快捷命令，Flink配置分发）
- 集成Hive相关配置至CDH Flink
- 兼容Flink1.10 Flink1.11版本至CDH
- 编译安装参考博客[https://www.cnblogs.com/abramgyb/p/14800347.html]
- 更多请参考博客[https://blog.csdn.net/guiyifei/article/details/109325980]
