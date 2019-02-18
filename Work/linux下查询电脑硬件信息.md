# Linux(Ubuntu)下查看电脑硬件配置  

Windows有鲁大师，Linux有命令行。  

## 相关命令  
系统硬件配置都在/proc目录里面，可以用命令查看里面的文件即可比如：cat/proc/cpuinfo查看cpu信息。

```
lspci               查看主板信息

free –m             查内存(total属性下显示的是内存的大小)

fdisk -l            查硬盘空间

df -h               查硬盘容量大小

top                 查内存进程负载

uptime              查运行时间负载情况

dmidecode -t memory 查看运行内存的详细信息
```

## 详细的参考资料  
[ubuntu下查看硬件配置-csdn](https://blog.csdn.net/chuanyu/article/details/46611793)  
[Linux下查看内存使用情况方法总结-博客园-坠落鱼](https://www.cnblogs.com/zhuiluoyu/p/6154898.html)