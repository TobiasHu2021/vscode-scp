# scp sync extension for VS code

这是一款面向服务器默认关闭 sftp 功能场景的使用 scp 来进行自动化同步文件的软件。

## 功能特点

- 保存自动同步
- 全局同步
- 忽略文件

## Requirements

使用前提条件：使用 ssh 命令将本机的密钥传送到服务器端，从而可以免密登录。

```
ssh-copy-id -i ~/.ssh/id_rsa

```

## 使用

1. 在电脑中通过 Ctrl+Shift+P 打开命令，输入并运行: vscode-scp: Config
2. 配置文件自动生成在.vscode/scp.json 中，按照自己的需求进行配置好。

## 更新日志

### 0.0.1

插件完成第一个版本

---

**Enjoy!**
