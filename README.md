# git-github-experiment
> A experiment about git&amp;github

---

12312 === test

## 1. Introduction

123123 21=32= =1


* git，版本控制系统
* github，代码托管平台
* git + github
  * 可以看作一种 **专门存放代码** 的云盘
  * 支持 **多人同时开发** 一个项目

---

* 设想一个场景...

---

* 所以我们需要 git + github

---

* 除了 **多人合作开发** 以外，git+github还可以：
  * 当云盘（配置文件、游戏存档、图床）
  * 搭建静态网站（个人博客、wiki百科）
    * [我的博客](https://yxhxianyu.fun/)
    * [OI Wiki](https://oi-wiki.org/)
  * 自动化部署与自动化测试
  * etc...

---

## 2. How to use

* 单人
  * 云盘、作业、博客
* 多人 + 有权限
  * 与认识的人合作
* 多人 + 有权限 + 多分支
  * 与认识的人合作
* 多人 + 无权限 + 多分支
  * 与不认识的人合作

---

## 3. 单人

* 初始化仓库
  * 在Github上新建一个仓库，并且clone到本地

* 本地to云端（push）
  ```
  git add .
  git commit -m "some comments"
  git push
  ```

* 云端to本地（pull）
  ```
  git pull
  ```

---

* “作业”：把本学期的Java作业上传到Github中
  * 记得把仓库权限改成private，不然到时候作业查重寄了（
* 为什么？
  * 学习是记忆与理解相促进的
  * 便于未来理解更复杂的git用法

---

## 4. 多人 + 有权限

* 多人合作！

* 大家说一下每个人的Github ID，我将所有人添加到今天实验仓库的contributors中

* clone今天的实验仓库（https://github.com/YXHXianYu/git-github-experiment）
  ```
  git clone git@github.com:YXHXianYu/git-github-experiment.git
  ```

* 然后在仓库内随意地修改吧~
  * 比如可以在README.md的末尾添加自己的id/名字缩写
  * 或者是新建一个特殊的文件
  * 然后把它push到github仓库中

---

* 本地to云端（push）
  ```
  git add .
  git commit -m "some comments"
  git push
  ```

* 云端to本地（pull）
  ```
  git pull
  ```

---

* 多分支
  * 设想这么一个场景...
  * 一个新模块要写10个小时，我写一半就需要保存代码了！但是目前代码还不能正常运行

* 查看目前所有分支 `git branch --all`
* 创建一个新分支 `git checkout -b your_branch_name`
* 切换一个分支 `git checkout another_branch_name`
* 将github上一个任意分支pull到当前分支 `git pull origin a_branch_name`
* 将当前分支push到github上一个任意分支 `git push origin a_branch_name`
* 将本地一个其他分支合并到当前分支 `git merge another_branch_name`

---

* 和开源社区（陌生人）合作
1. fork
2. 修改自己fork出来的仓库
3. 提交PR

---

## 5. 其他

* 希望大家玩的开心，能在这次活动中学到知识
* 讨论
* “作业”
* BJTUGE




*asdfghjkl
