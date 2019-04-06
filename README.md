# SSR-Bash-Python
#安装
```
wget -N --no-check-certificate https://raw.githubusercontent.com/lllvcs/SSR-Bash-Python/master/install.sh && bash install.sh
```

#卸载
```
wget -N --no-check-certificate https://raw.githubusercontent.com/lllvcs/SSR-Bash-Python/master/uninstall.sh && bash uninstall.sh
```

#自检
```
wget -N --no-check-certificate https://raw.githubusercontent.com/lllvcs/SSR-Bash-Python/master/self-check.sh && bash self-check.sh
```



#Debian 9 设置自启动可能会报错，请进行如下设置
```
vim /etc/fstab

tmpfs /run tmpfs nosuid,noexec,size=20M,nr_inodes=4096 0 0
```
