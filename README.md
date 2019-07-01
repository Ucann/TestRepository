# TestRepository

- 借助github托管项目代码

        repository 一个开源项目又有一个仓库
        star 收藏 方便查找 your stars
        fork 复制克隆项目 fork项目独立存在
        pull request 发起请求 create pull request --> merge pull request --> confirm merge
        watch 关注
        issue 事务卡片（发现bug 要讨论）

        github主页
        仓库主页
        个人主页

- 仓库管理

        删除文件： 点击`commits`查看被删除文件信息
        搜索文件： find file（快捷键 `t` 或 `T`）

- Github Issues
        
        双方都有权限close issue

- 如何为开源项目做出贡献

        1. 新建issue 

                提交使用问题或者建议或者想法

        2. Pull request 

                步骤：
                fork项目
                修改自己仓库的项目代码
                新建pull request
                等待作者操作（合并）

---

## [Git](https://git-scm.com/download/win)  
![Git Logo](images/gitlogo.jpg)
通过`git`管理`github`托管项目代码
        
- ### Git工作区域
1. Git Repository（Git仓库）最终确定的文件保存到仓库，成为一个新的版本，并对他人可见
2. 暂存区 暂存已经修改的文件最后统一提交到Git仓库中
3. 工作区（Working Directory）添加、编辑、修改文件等动作
工作区`git add filename` --> 暂存区`git commit -m "description"` --> Git仓库    `git status` 

- ### Git基础设置

``` git
# 该设置在GitHub仓库主页显示谁提交了该文件
$ git config --global user.name 'Ucann'
$ git config --global user.email '207825248@qq.com'

$ mkdir repositories
$ cd repositories/
# 在文件内初始化git（创建git仓库） .git文件存储仓库所有信息
$ git init


```















[Reference](https://github.com/yezhaodan/-Git/blob/master/GitLearning.md)
