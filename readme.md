<!--
 * @Author: Espero
 * @Date: 2021-04-13 22:55:43
 * @LastEditTime: 2021-04-13 23:24:09
 * @FilePath: /my_first_git_project/readme.md
 * @Description: file contenth
-->
# Git操作
### 1.git init  进入该文件目录后，首先初始化 

### 2.git status    检测当前目录下的文件状态 
#### 三种状态的变化：
####  (1).红色：新增的文件/修改了原来的文件  git add "文件名" 或者 "git add ." 一次性添加所有 
####  (2).绿色：git已经管理起来了，但是未生成一个版本  git commit -m "记录你的版本描述信息"

### 3.查看版本信息 git log


# 其他 
### 1.查看git用户名 git config user.name
### 2.查看git绑定的邮箱 git config user.email 
### 3.修改git用户名称 git config --global user.name yourName
### 4.修改git绑定的电子邮箱 git config --global user.email yourEmail

# 注
### 在第一次安装git时需要进行个人信息配置  用户名 和 邮箱