<!-- title : Server Performance -->

# 服务器性能用到的知识 #

* Load
* CPU
* Mem
* 磁盘I/O
* 网络I/O

# Load #

系统负载指运行队列的平均长度，也就是等待CPU的平均进程数

可以通过`cat /proc/loadavg` `w` `top`等命令获取

推荐一篇文章[[http://blog.scoutapp.com/articles/2009/07/31/understanding-load-averages|Understanding Linux CPU Load]]

# CPU #

`top` `atop` `htop`
获取CPU信息`cat /proc/cpuinfo`

其中%wa指CPU等待磁盘写入完成的时间

`vmstat` `sar` `iostat`

# Mem #

`free` `vmstat` `top` `cat /proc/meminfo`

# 磁盘I/O #

`iostat`

# 网络I/O #

`netstat`

# Read More #

* [Linux服务器性能小结](http://blog.chinaunix.net/uid-27127953-id-3333176.html)
* [linux wa%过高，iostat查看io状况](http://www.cnblogs.com/mfryf/archive/2012/03/12/2392000.html)

# History #

Create 2013/02/21
