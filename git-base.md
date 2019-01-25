学习作业：

1. #### 版本控制一共包括哪三个？有什么特点？

   - 本地版本控制系统：本地进行，记录文件的历次更新差异
   - 集中化版本控制系统：集中操作，有一台中央服务器。
   - 分布式版本控制系统：把代码仓库完整的镜像下来，每一次都进行一次完整备份

2. #### 安装git，并且要开始用git bash工具

3. #### 利用git 的bash 进行git add git commit git status git log等操作

4. #### 在note仓库中添加git-basic.md文件 文件内容要写git基础的学习笔记

   ------

   #### git基础笔记

   | 步骤                         | 命令                                                         |
   | ---------------------------- | ------------------------------------------------------------ |
   | 1.设置用户名和邮箱           | git confing --list (查看设置信息)   git confing --global user.name（设置用户名）    gitconfing --global user.email（绑定邮箱） |
   | 2. 克隆远程仓库到本地        | git clone http://github.com/mayD/nodes                       |
   | 3.在本地增删改               | touch a.txt                                                  |
   | 4.查看仓库状态               | git status                                                   |
   | 5.将工作区的更改提交到缓存区 | git add/rm 文件                                              |
   | 6.将缓存区的提交到本地仓库   | git commit -m "nodes"                                        |
   | 7.将本地仓库更改到远程仓库   | git push                                                     |
   | 8.记录密码                   | git config --global credential.helper store                  |
   | 9.查看或搜索提交历史         | git log                                                      |

   具体操作连接：
     https://github.com/liujinmenghaoren/myCourse/blob/master/web1/class4.md