# volatility_mimikatz
基于volatility框架的mimikatz插件，实现从Windows vista，Windows 7休眠文件中提取明文密码，在原基础上增加Windows 8的支持。
由于volatility目前不支持Win7以上系统的休眠文件的解析，可以通过hibr2bin.exe工具将Win8休眠文件转为原始内存镜像文件，然后通过mimikatz.py插件进行明文密码提取。

参考：

https://github.com/gentilkiwi/mimikatz

https://github.com/RealityNet/hotoloti/tree/master/volatility
