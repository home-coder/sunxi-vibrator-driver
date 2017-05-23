# sunxi-vibrator-driver
基于A33的马达，内部使用hrtimer，向上提供sys节点。使用regular驱动。
后期支持gpio兼容。

本仓是一个持续工程，涉及将Android系统重新过一遍的过程。类似之前can总线，和spi等。
不过这个的一个好处是驱动简单，不需要底层协议支持。可以随意定制内核向上接口。

参考链接
http://blog.csdn.net/u010164190/article/details/51866419

http://blog.csdn.net/zhangchiytu/article/details/7067112
