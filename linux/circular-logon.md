#####Reason
修改了/etc/profile 添加了环境变量，重启后导致循环登录

#####进入文本编辑台

ctrl+alt+F5

#####修改/etc/profile
######problems:
1)  "'/usr/bin' is not included in the path"

/usr/bin/sudo /ur/bin/vi /etc/profile

2)  "vi命令删除字"

x
