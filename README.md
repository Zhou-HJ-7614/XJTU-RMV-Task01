# Task01
我按照双系统教程安装，电脑为windows10专业版，CPU为Intel（R） Core（TM） i7-6700HQ CPU @ 2.60GHz ，内存8G，C盘120G，D盘78.1G 
在最后安装时出现了“致命错误”：执行'grub-install /dev/sda'失败。 
点击确定后重启，并没有自动出现选择系统的界面，而是“Reboot and Select proper Boot device or Insert Boot Media in selected Boot device and press a key” 
通过重插启动盘，调整系统启动顺序，发现ubuntu没有装好 
最后仔细阅读指南，发现是新建EFI对应的设备选错了，改正后系统基本正常。
