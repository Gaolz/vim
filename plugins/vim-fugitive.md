vim-fugitive
============

> 项目主页：[https://github.com/tpope/vim-fugitive](https://github.com/tpope/vim|fugitive)

> a Git wrapper so awesome, it should be illegal

> [vimcasts.org](http://vimcasts.org/episodes/)

| **fugitive**  | **git**         | **function**                                        |
| ------------  | ----------------| ----------------------------------------------------|
| :Gstatus      | git status      | 显示有变更的文件                                    |
| :Gwrite       | git add %       | 对当前文件执行 git add 命令                         |
| :Gread        | git checkout %  | 将当前文件反转至上次的 checkout 状态                |
| :Gremove      | git rm %        | 从 git 中删除该文件，且在 vim 中删除该文件的 buffer |
| :Gmove        | git mv %        | 重命令当前的文件名以及对应的 buffer 名              |
| :Gcommit      | git commit      | 提交，可以使用 ctrl + n 来补全                      |
| :Gblame       | git blame       | 查看当前文件每一行的最后一次修改是谁完成的          |
| :Gedit        |                 | 允许浏览其他分支文件的当前状态                      |
| :Glog         | git log         | 查看提交日志                                        |
| :Ggrep        | git grep        | search for 'findme' in tag 'tagname'                |
| :Gbrowse      | git instaweb    | 打开 GitHub 上面的当前(对应)文件                    |



#### 命令详解

> :Gstatus

打开一个 git status 命令的窗口，在这个窗口中你可以使用一下快捷键。Ctrl+n, Ctrl+p


> :Gdiff

比较两个文件的不同，两个文件分别显示在 vim 的两个 window 中。

**注意， Gdiff 打开的两个窗口，左边的永远是缓冲区里的内容，右边的永远是当前正在编辑文件的内容。**

:diffget 从另一个 diff 窗口中拉取当前光标所在的内容。

:diffput 将当前光标所在的修改过的内容 put 到另一个窗口中。

可以使用 visual 模式修改仅仅选择的几行内容。


