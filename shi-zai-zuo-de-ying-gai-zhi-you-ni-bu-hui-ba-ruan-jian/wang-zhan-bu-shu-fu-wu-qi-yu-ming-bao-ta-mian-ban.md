# 网站部署：服务器、域名、宝塔面板

## 安装完宝塔后 SSH ROOT账号无法登陆

1. SSH 22端口放行
2. Linux工具箱重置一次密码
3. ```
   ssh-keygen -R xx.xx.xxx.xxx && ssh-keyscan xx.xx.xxx.xxx >> ~/.ssh/known_hosts
   ```
