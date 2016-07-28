NERD Commenter
==============

> 项目主页：[https://github.com/scrooloose/nerdcommenter](https://github.com/scrooloose/nerdcommenter)

> 代码注释

### Using
---------

##### 常用
- `<leader>cc`  - 注释当前行
- `<leader>ci`  - 注释选中行（反转注释）
- `<leader>c$`  - 注释当前光标到改行结尾的内容
- `<leader>cu`  - 取消注释

##### 冷门
- `<leader>cn`  - 注释当前行
- `<leader>c[space]`  - 如果被选区域有部分被注释，则对被选区域执行取消注释操作，其它情况执行反转注释操作
- `<leader>cs`  - sexy 注释， 代码开头介绍部分通常使用该注释
- `<leader>cy`  - 添加注释，并复制被添加注释的部分
- `<leader>cA`  - 调转到该行结尾添加注释，并进入编辑模式
- `<leader>ca`  - 转换注释的方式，比如：/**/, //, =begin =end, #
- `<leader>cl`  - 左对齐，针对 /**/
- `<leader>cb`  - 右对齐，针对 /**/

##### 具体常见用法：

`ESC`(进入命令模式) > `v`(进入 visual 模式) > `12gg`(vim 会选中当前行到第12行的内容) > `<leader>ci`(添加注释或取消注释)

##### 其他
----------

`help <leader>` 查看 `<leader>` 的说明及使用。

`<leader>` 默认是 `"\"`, 反斜线

在 `.vimrc` 中添加 `let mapleader = ","` 可以把 `<leader>` 设置成 `","`, 或者其他任意符号。 


