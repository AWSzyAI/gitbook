# SSH

* [ ] [SSH端口转发命令](https://zhuanlan.zhihu.com/p/148825449)

```bash
ssh username@hostname
ssh -L 主机A端口X:主机C:主机C端口Z username@hostname//
//-L 本地端口转发
ssh -L [收听接口:]收听端口:目标主机:目标端口 username@hostname
```
