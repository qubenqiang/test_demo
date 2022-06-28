# Git

---

## 配置全局用户信息

**git config --global user.name ""**

**git config --global user.email ""**

---

## 终端基本命令

- `ls` 常看当前目录的文件夹
  - `ls -al` 查看全部文件包括隐藏文件
- `mkdir` [文件夹名字] 创建文件夹
- `cd` 切换目录
- `touch` [文件] 创建文件
- `clear` 清屏
- `pwd` 查看当前终端所在的文件夹 (目录)
- `cat` 读取文件内容
- `rm -rf` [文件名]  删除文件夹及里面的文件

## Git 提交命令

- `git init` 初始化仓库
- `git status` 检查文件状态
  - `git status -s` 精准查看
- `git add [. 文件名]`
- `git commit -m "名字"`
- `git log` 日志
- `git reset --hard` 回退到哪个版本
- `git reflog` 操作日志
- `git checkout --[文件名]` 利用本地仓库的版本覆盖工作区修改的版本
  - `git checkout [.]` 

---

## .gitignore

```
#  注释
/  目录
*  匹配任意字符
!  取反
** 匹配任意中间目录
```

---

## 密钥

ssh-keygen -t rsa -c "邮箱地址"

C => 用户 => 用户名 => .ssh => id_rsa 和 id_rsa.pub