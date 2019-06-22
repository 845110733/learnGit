Git is a distributed version control system.
Git is a free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of flies.

This file has changed.

Creating a new branch is quick and simple.

test git merge --no-ff


stash的应用场景：

（网友）我个人觉得场景是这样的。设A为游戏软件 
1、master 上面发布的是A的1.0版本 
2、dev 上开发的是A的2.0版本 
3、这时，用户反映 1.0版本存在漏洞，有人利用这个漏洞开外挂 
4、需要从dev切换到master去填这个漏洞，正常必须先提交dev目前的工作，才能切换。 
5、而dev的工作还未完成，不想提交，所以先把dev的工作stash一下。然后切换到master 
6、在master建立分支issue101并切换. 
7、在issue101上修复漏洞。 
8、修复后，在master上合并issue101 
9、切回dev，恢复原本工作，继续工作

Now, the bug has been fixed. 
And I have to go back to the dev-branch to work.
