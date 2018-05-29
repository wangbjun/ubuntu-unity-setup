# Ubuntu_Desktop
总结介绍一下Linux系统安装和优化配置，但是主要是Ubuntu 16.04，其它Linux发行版也可以作为参考

完事开头难，很多人接触Linux第一步就被挡在了安装系统这个步骤上，毕竟市场上面在售的搭载Linux操作系统的电脑屈指可数，而且据我观察，很多程序员对于电脑硬件
也是一窍不懂，更不用说安装系统了，如果你对安装windows操作系统有一定的经验，那么安装Linux系统也不是多大的事情！


无论是安装windows还是Linux，或者还是Android等操作系统，套路都是一样的，操作系统本质上是一段程序代码，我们需要把这段代码放在硬盘某个地方，
然后让CPU去加载运行，把东西拷贝到硬盘上面很简单，但是CPU怎么知道那段代码在什么地方呢？所以安装系统最后有一步非常重要，那就是设置引导设备和引
导分区。细节不多说，但是总体来说，安装操作系统也就几个大步骤：

1. 第一步，硬盘分区和格式化，Windows、Mac、Linux所使用的文件系统都不一样，所以必须格式化成所需要的格式。
2. 第二步，copy系统文件到硬盘。
3. 第三步，设置引导设备和引导分区（假如有多个设备和分区的话）。

不过实际安装过程没这么复杂，现在大部分操作系统都是傻瓜式安装，你只需要填一下基本信息，做一些选择即可，相当简单！

本文主要分为以下几个部分：
1. [制作U盘启动盘](https://github.com/wangbjun/ubuntu_desktop_setup/blob/master/1.start_up_disk.md)
2. [使用U盘引导设备](https://github.com/wangbjun/ubuntu_desktop_setup/blob/master/2.boot_from_usb.md)
3. [安装系统](https://github.com/wangbjun/ubuntu_desktop_setup/blob/master/3.install.md)
4. [系统设置](https://github.com/wangbjun/ubuntu_desktop_setup/blob/master/4.setup.md)
5. [日常应用安装](https://github.com/wangbjun/ubuntu_desktop_setup/blob/master/5.application.md)
6. [编程工具安装](https://github.com/wangbjun/ubuntu_desktop_setup/blob/master/6.code_tool.md)
7. [编程环境安装](https://github.com/wangbjun/ubuntu_desktop_setup/blob/master/7.env.md)
