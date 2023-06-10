# 0. See:
- [windows7系统怎么激活？](https://www.zhihu.com/question/50617254)

# 1. 延长试用期到120天
在Windowsx 7 30天试用到期前，使用“slmgr.vbs -rearm”指令，系统就可以再次延长30天使用时间，这个命令微软允许的最大重置次数是3次，一次30天，也就是一共120天的时间

# 2. 注册表重置，最多8次激活“延长试用期”功能
- 我们也可以通过注册表重置，当我们在使用系统命令激活三次以后，“slmgr.vbs -rearm”命令就无法再次使用了。此时，可以选择使用注册表重置的方式来重置激活状态命令。
- 进入编辑器后，我们依次打开”HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsNT\CurrentVersion\SL“文件，然后将“SkipRearm”的键值修改为“1”，就可以再次使用重置命令。此键值可以修改次数为8次。

# 3. 永久激活(kms激活)
- [Windows7专业版系统永久激活的方法](https://www.xitongzhijia.net/xtjc/20170323/94459.html)
