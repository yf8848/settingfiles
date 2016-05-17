# my ubuntu settings -zwding
#### 包括.bashrc和.vimrc
#### .bashrc里面有自己的命令行个性化设置
#### .vimrc包含自己vim的全部设置
- - -
##### .vimrc
针对c++，python，markdown等多种语言的设置，采用vim
bundle插件管理器，内置多种插件（后面列出）</br>
##### 配置步骤
* 在terminal运行下面这个命令<br>
<code>
bash <(curl https://github.com/Oozwding/settingfiles/blob/master/installvimrc.sh -L)>
</code><br>
<b>Attention</b>:这个操作会将你原来的设置备份到你的家目录下,所有设置在Ubuntu 16.04测试通过
* 打开vim，输入:BundleInstall<br>
使用bundle安装插件，有个yumyoucompleteme插件安装比较麻烦，具体安装方法参考[github项目地址](
https://github.com/Valloric/YouCompleteMe)
* 配置完成
##### Plugins
[tomasr/molokai](https://github.com/tomasr/molokai)<br>
[scrooloose/nerdtree](https://github.com/crooloose/nerdtree)<br>
[tpope/vim-markdown](https://github.com/tpope/vim-markdown)<br>
[suan/vim-instant-markdown](https://github.com/suan/vim-instant-markdown)<br>
[bronson/vim-trailing-whitespace](https://github.com/bronson/vim-trailing-whitespace)<br>
[kien/rainbow_parentheses.vim](https://github.com/kien/rainbow_parentheses.vim)<br>
[bling/vim-airline](https://github.com/bling/vim-airline)<br>
[vim-airline/vim-airline-themes](https://github.com/vim-airline/vim-airline-themes)<br>
[ervandew/supertab](https://github.com/ervandew/supertab)<br>
[Raimondi/delimitMate](https://github.com/Raimondi/delimitMate)<br>
[scrooloose/syntastic](https://github.com/scrooloose/syntastic)<br>
[scrooloose/nerdcommenter](https://github.com/scrooloose/nerdcommenter])<br>
[nathanaelkane/vim-indent-guides](https://github.com/nathanaelkane/vim-indent-guides)<br>
[godlygeek/tabular](https://github.com/godlygeek/tabular)<br>
[MatlabFilesEdition](https://github.com/MatlabFilesEdition)<br>
[Valloric/YouCompleteMe](https://github.com/Valloric/YouCompleteMe)<br>
[Valloric/ListToggle](https://github.com/Valloric/ListToggle)<br>
[SirVer/ultisnips](https://github.com/SirVer/ultisnips)<br>
[honza/vim-snippets](https://github.com/honza/vim-snippets)<br>
[Bterryma/vim-multiple-cursors](https://github.com/Bterryma/vim-multiple-cursors)<br>
[Bhdima/python-syntax](https://github.com/Bhdima/python-syntax)<br>
[Bmajutsushi/tagbar](https://github.com/Bmajutsushi/tagbar)<br>
[vim-scripts/taglist.vim](https://github.com/vim-scripts/taglist.vim)<br>
* 欢迎各位入坑
