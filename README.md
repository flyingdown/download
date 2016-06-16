# download
python实现多线程下载

# thanks
有参考网上对HTTP协议的理解，最终实现对于普通http协议文件的下载

# how to use
该程序是在windows的python环境中编写的，依赖requests、argparse库
运行：python download.py uri [线程数]

    D:\python\urltest>python download.py http://www.sae.sinacdn.com/.app-stor/docs/downloads/Cyberduck-Installer-4.2.1.exe
    下载资源大小为：13 MB
    下载进度：[>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>] 100.00%
    下载完成

    D:\python\urltest>

# bug
程序还有问题，现测试对zip文件的下载有问题，调试很长时间也不知道问题出在什么地方，若有朋友知道，往指出问题，多谢！
