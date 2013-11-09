Git/Github练习
============

注意：新建的所有分支都需要提交到Github仓库中，并且即使`merge`了，Github仓库中的这些
分支也不应该删除

1. 从github上把该项目仓库复制到自己的Github帐号下

2. 把自己帐号下的项目仓库克隆到本地

3. 切换到该项目的`practice`分支，完成其中的`README.md`所描述的任务

4. 新建一个`main.c`文件，实现输出`hello, world!`的功能，并提交到仓库中

5. 编译并运行，此时使用`git status`查看状态，如果编译的中间文件或者目标文件在
`Untracked files`中，请修改`.gitignore`文件以忽略这些文件

6. 删除此文件所在目录下的`LICENSE`文件并提交到仓库中

7. 新建分支为`python-hello`并切换到此分支下

7. 重命名`main.c`文件为`main.py`，并将其中的C语言代码改为Python代码，实现相同的功能，
然后提交

8. 想办法找回`LICENSE`文件并提交。注意：这一步可能会新建分支，如果你新建了分支，请记得提交
到Github的仓库中

9. 回到`master`分支，新建`main.py`文件并使用Python实现输出斐波那契数列中的第100个数
的功能，然后提交此文件

10. 此时`merge`第7步新建的分支，并处理冲突（保留两个文件中的所有功能，即既打印
`hello, world!`，又打印第100个斐波那契数）

11. 把所有分支都提交到Github仓库中

12. 向`njuopn/git-practice`发起`pull request`，练习即完成
