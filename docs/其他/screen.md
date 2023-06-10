GNU *Screen*是一款由GNU计划开发的用于命令行终端切换的自由软件。用户可以通过该软件同时连接多个本地或远程的命令行会话，并在其间自由切换。Screen不可以在Windows平台上使用



#### 创建会话

```bash
screen -S [会话名]
```



#### 查看所有会话

```bash
screen -ls
```



#### 恢复会话

```bash
screen -dr/-r [会话名或ID]
```

注：选择”-dr“还是”-r“取决于会话是否处于”detached“的状态



#### 删除会话

1. 进入会话后输入

   ```bash
   exit
   ```

2. 在screen会话外

   ```bash
   screen -S [会话名或ID] -X quit
   ```

   



#### 进入copy mode

作用：查看历史输出

快捷键：`ctrl+a+[`

退出：`Esc`





