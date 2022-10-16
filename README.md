# yazi
c++ framework


workflow:
make plugin
make
./main &
netstat -an | grep :8080
ps -elf | grep main

## 此项目设计一些技术：
* 造轮子技术；
* docker的使用；
* 常用服务器，client的一些东西；
* 常用配置文件的解析；
* 线程池；

启动容器：
docker run -it -p 22:22 -v D:\yazi\yazi:/root/yazi --name centos centos
/usr/sbin/sshd


# 项目文档：
https://hkrb7870j3.feishu.cn/docx/doxcn4Qjv9EXC24N8817CyEQwwh

# 视频：
https://www.bilibili.com/video/BV1hV4y1J7Ls/?spm_id_from=333.999.0.0&vd_source=ddaa7cd556186574491ea632ad077d44