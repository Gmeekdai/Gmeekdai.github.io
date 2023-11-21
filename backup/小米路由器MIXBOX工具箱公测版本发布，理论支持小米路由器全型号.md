介绍
工具箱MIXBOX公测发布，Monlor Tools不再更新。新版本有以下改变：

MIXBOX

工具箱尝试支持更多的路由器固件，正在努力中，需要测试
去掉随时可能被小米封的web界面
移除针对小米路由器设置的功能，如修改samba路径和禁用迅雷等，合并到新的插件MIWIFI
增加一个应急功能，在用户目录创建文件uninstall_mixbox即可卸载工具箱
增加几个工具箱常用命令，applist:用于管理插件列表，cru:定时任务管理，mbdb:工具箱数据库，基于uci，mixbox:工具箱命令行交互界面
工具箱增加目录，/etc/mixbox/mbdb:存放数据文件，/etc/mixbox/var/run:存在程序进程pid文件，/etc/mixbox/var/log:工具箱日志目录
工具箱现在不会特意去兼容某个型号，比如R3上的Aria2问题，只考虑CPU架构，mips/arm等，所以如果R3/R1CM发现程序不兼容的情况，可以选择自己替换程序，或同时安装Monlor-Tools工具箱
插件安装去掉了离线安装的功能，后续会加入进来，给用户提供一个自己修改打包插件的机会