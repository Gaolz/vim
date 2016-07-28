tagbar
======

> 项目主页：[https://github.com/majutsushi/tagbar](https://github.com/majutsushi/tagbar)

> a class outline viewer for Vim

> `大纲式导航`：可以将正在编辑的文件生成一个大纲, 包含类/方法/变量等, 可以选中快速跳转到目标位置。


##### Config

In `.vimrc`

- nmap `<leader>`tb :TagbarToggle`<cr>`     ` 热键启动`
- let g:tagbar_autofocus=1                  `启动时自动focus`
- let g:tagbar_width=30
```
let g:tagbar_type_ruby = {
  \ 'kinds' : [
    \ 'm:modules',
    \ 'c:classes',
    \ 'd:describes',
    \ 'C:contexts',
    \ 'f:methods',
    \ 'F:singleton methods'
  \ ]
\ }
```

##### 依赖

- `Exuberant ctags`

```
# ubuntu
sudo apt-get install ctags

# centos
sudo yum install ctags

# mac
brew install ctags
```
