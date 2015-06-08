#vim配置方法#
这篇文档用来总结使用vim过程中遇到的一些问题，同时记录一些技巧。
##vim一般配置##
##vim插件配置##
###NEARTree的安装配置###
* 下载
>下载地址：<http://www.vim.org/scripts/script.php?script_id=1658>
* 安装
>解压缩下载的NEARDTree，把 plugin/NERD_tree.vim 和doc/NERD_tree.txt分别拷贝到~/.vim/plugin 和 ~/.vim/doc 目录。
* 配置
<p><code>
> " 设置NerdTree快捷键<br />
> `map <F3> :NERDTreeMirror<CR>`<br />
> `map <F3> :NERDTreeToggle<CR>`<br />
</code></p>