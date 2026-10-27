# 终端命令手册

> 我的命令复习卡。规则:新学的加到对应分类;每周日遮住「作用」列自测一遍。

## 怎么用这个文件

1. 学到一个新命令 → 加到最下面,四列都填
2. 周日复习:遮住「作用」和「例子」,只看命令,说出它干什么
3. 连续三次都记得 → 标 ✅ 已掌握

---

## 一、目录与文件

| 命令 | 全称 | 作用 | 例子 | 危险 |
|---|---|---|---|---|
| `pwd` | print working directory | 显示当前所在路径 | `pwd` | 安全 |
| `ls -la` | list+long+all | 列出所有文件(含隐藏文件) | `ls -la` | 安全 |
| `cd 路径` | change directory | 切换目录 | `cd ~/code/lifeos` | 安全 |
| `grep` | global regular expression print | 搜索文本 |
| `man` | manual | 手册 |
| `ps` | process status | 进程状态 | `ps a.txt` | 安全 |
| `df` | disk free | 磁盘剩余 |
| `du` | disk usage | 磁盘占用 |

## 二、文件操作

| 命令 | 作用 | 例子 | 危险 |
|---|---|---|---|
| `touch 文件名` | 建空文件 | `touch a.txt` | 安全 |
| `rm 文件名` | remove |删除文件 | `rm a.txt` | ⚠️ 不可恢复 |
| `cp 文件名` | copy | 复制文件 | `cp a.txt` | 安全 |
| `mv 文件名` | move | 移动/改名文件 | `mv a.txt` | 安全 |
| `cat` | catenate | 输出文件内容 | `cat a.txt` | 安全 |
| `touch` | touch | 建空文件/更新时间 | `touch a.txt` | 安全 |
| `echo` | echo | 回声➡️输出文字 |
| `sudo` | superuser do | 以管理员身份执行 | `sudo ...` | 安全 |
| `chmod` | change mode | 改权限 |
| `ssh` | secure shell | 安全远程登录 |


## 三、Git

| 命令 | 作用 | 例子 | 危险 |
|---|---|---|---|
| `git status` | 看当前改动 | `git status` | 安全 |
| `git add .` | 暂存所有改动 | `git add .` | 安全 |
| `git init` | 初始化 | `git init` | 安全 | initialize |
| `git commit` | 提交 | `git commit` | 安全 |
| `git push` | 推送 | `git push` | 安全 |
| `git pull` | 拉取 |
| `git clone` | 克隆 |
| `git branch` | 分支 |
| `git merge` | 合并 |
| `git log` | 日志 |
| `git diff` | 差异 |
| `git remote` | 远程 |
| `git status` | 状态 |
| `git config` | 配置 |

## 四、npm / pnpm

| 命令 | 作用 | 例子 | 危险 |
|---|---|---|---|
|  |  |  |  |

---

## 五、参数
| 参数 | 全称 | 作用 |
|---|---|---|
| -v | verbose/version | 详细输出/版本 |
| -f | force | 强制 |
| -r | recursive | 递归（对文件夹生效） |
| -a | all | 全部（含隐藏文件） |
| -l | long | 场格式（详细信息如权限、大小、时间） |
| -h | human/help | 人类可读/帮助 |
| -n | number | 显示行号 |
| S | Size | 按大小排序（大写！）|
| t | time | 按修改时间排序 |
| r | reverse | 反转顺序 |


## 待补 / 还不熟的

- [ ] `grep` 怎么用
- [ ] `chmod` 是干什么的


## 坑

| `ls -lh <dir>` | "< >"不是照抄，而是换成自己的东西 
     例如：ls -lh ~/code/lifeos

-s 是显示块数  -S 是按大小排序