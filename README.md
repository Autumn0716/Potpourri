# Potpourri
本人学习2020 年 missing-semester所做的一些作业题目,
  (这里是第十,十一章),可以参考往日仓库.
 参考链接:[Potpourri](https://missing.csail.mit.edu/2020/potpourri/)

  也方便自己进行查阅,时刻温习学过的知识,并且逐渐修正自己在编程 shell,python 等程序时存在的思路优化和语法错误等等.


**提示:**
Potpourri 这一节其实并没有作业,因此只是设计一些课堂上比较好玩的有意思的东西记录下来.


1.**键盘映射**
针对于 mac 系统,可以在设置里面
(**设置->键盘->键盘快捷键->截屏**)
找到屏幕截图,可以使用所选内容(比较通用)映射为 f5
(因为 f5 在 mac 上是听写功能,之前我映射为两次地球仪键是听写),因此不会通常用到,然而实际上 mac 功能键有很多是用不到的,比如说 f3,f4(日常 *spotlight* 平替 *raycast*),f5-f9,很多键是没有必要的,更多的功能等待扩展.

2.**VPN**
这是一则关于 VPN 的[不见光的讨论](https://web.archive.org/web/20230710155258/https://gist.github.com/joepie91/5a9909939e6ce7d09e29)
VPN 充其量只是一种更换互联网服务提供商的方式。您的所有流量看起来都来自 VPN 提供商，而不是您的“真实”位置，并且您所连接的网络只会看到加密的流量

**一些学习的tips**:
- 学习更多使用键盘,减少使用鼠标
- 习惯使用编辑器比如(vim)
- 学习如何自动化流程,简化重复性任务
  
**选择Python|Bash or 其他语言?**
- bash 通常对于简单,短小的特定命令很有用处,难以处理较复杂的任务.
- 对于大型任务建议使用 Python|Ruby
  
**各种软件包和工具存储在什么地方**?**如何引用他们**?
`/bin`和`/lib`**又是什么**?

/bin - Essential command binaries
/bin 基本命令二进制文件
/sbin - Essential system binaries, usually to be run by root
/sbin - 基本系统二进制文件，通常由 root 运行
/dev - Device files, special files that often are interfaces to hardware devices
/dev - 设备文件，通常是硬件设备接口的特殊文件。
/etc - Host-specific system-wide configuration files
/etc 主机特定的系统范围配置文件
/home - Home directories for users in the system
/home 系统中用户的主目录
/lib - Common libraries for system programs
/lib 系统程序的通用库
/opt - Optional application software
/opt 可选应用软件
/sys - Contains information and configuration for the system (covered in the first lecture)
/sys 包含系统信息和配置（ 第一讲已介绍）
/tmp - Temporary files (also /var/tmp). Usually deleted between reboots.
/tmp - 临时文件（也称为 /var/tmp ）。通常在系统重启后删除。
/usr/ - Read only user data
/usr/ ——只读用户数据
/usr/bin - Non-essential command binaries
/usr/bin 非必要的命令二进制文件
/usr/sbin - Non-essential system binaries, usually to be run by root
/usr/sbin - 非必要的系统二进制文件，通常由 root 运行
/usr/local/bin - Binaries for user compiled programs
/usr/local/bin - 用户编译程序的二进制文件
/var - Variable files like logs or caches
/var - 变量文件，例如日志或缓存
