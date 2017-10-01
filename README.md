# vimrc
Quick way to initialize my Vim

Included .vimrc:  
<https://github.com/amix/vimrc/blob/master/vimrcs/basic.vim>

Included Plugins:
```vim
Plugin 'VundleVim/Vundle.vim' " Plugin manager
" My plugin
Plugin 'NLKNguyen/papercolor-theme' " Theme
Plugin 'Raimondi/delimitMate' " Auto close braces
Plugin 'scrooloose/nerdtree' " File explorer
```
Others settings:
```vim
" Plugin settings
colorscheme PaperColor
set background=light
map <C-n> :NERDTreeToggle<CR>

" [+] Line number
set nu
```

## Install Vundle and .vimrc
```terminal
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
wget https://raw.githubusercontent.com/crucialbit/vimrc/master/.vimrc -O ~/.vimrc
```
## Install Plugin
```vim
:PluginInstall
```
## Disable auto comment
Temp
```vim
:set formatoptions-=cro
```
General
```vim
autocmd FileType * setlocal formatoptions-=c formatoptions-=r formatoptions-=o
```
