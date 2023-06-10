#### **拉取和上传出现“gnutls_handshake() failed: The TLS connection was non-properly terminated”**

```bash
git config --global http.https://github.com.proxy socks5://127.0.0.1:1080
#取消代理
git config --global --unset http.https://github.com.proxy
```

源：https://blog.csdn.net/qianbin3200896/article/details/127511105



#### 命令行提交修改基本指令

```bash
git add .
git commit -m"info"
git push origin [branch]
```





