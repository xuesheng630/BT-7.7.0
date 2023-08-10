# BT-7.7.0
***
+ ### 转载自 [**宝塔降级7.7.0方法**](https://blog.fqidc.cn/blog1/index.php/archives/285/)
+ ### 纯原版安装宝塔7.7.0：
```
wget -O install.sh http://blog.fqidc.cn/bt/install_6.0.sh && bash install.sh
```
___
+ ### 宝塔降级7.7.0
```
wget https://cdn.jsdelivr.net/gh/xuesheng630/BT-7.7.0/LinuxPanel-7.7.0.zip
```
```
unzip LinuxPanel-7.7.0.zip
```
```
cd panel
```
```
bash update.sh
```
+ ### 执行以下脚本，解决强制登录宝塔账号提醒：
```
rm -f /www/server/panel/data/bind.pl
```

