# ==========run_remote.py================
## 安装tmate终端共享工具，并将共享信息提交到https://file.zmkk.fun/脚本 
查看提交的信息： https://file.zmkk.fun/user_name.txt
运行脚本前需要修改173行和279行的user_name的值
# ==========run_remote.py================

# ==========root.sh================
## Ubuntu Proot 环境安装脚本 
在某些环境中，您可能需要一个完整的Ubuntu环境来运行上述ArgoSB脚本。以下是一个无需root权限的Ubuntu Proot环境安装脚本，可以帮助您在任何支持的系统上快速创建一个Ubuntu环境。

### 一键安装命令
 ``` cd ~ && wget https://raw.githubusercontent.com/zhumengkang/agsb/main/root.sh && chmod +x root.sh && ./root.sh ```
curl一键安装命令Proot
``` cd ~ && curl -sSL https://raw.githubusercontent.com/zhumengkang/agsb/main/root.sh -o root.sh && chmod +x root.sh && ./root.sh ```
基本命令
```
./root.sh          # 安装Ubuntu Proot环境
./root.sh del      # 删除所有配置和文件
./root.sh help     # 显示帮助信息
./start-proot.sh   # 启动Proot环境
```
# ==========root.sh================

