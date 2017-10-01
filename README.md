# vimrc
Quick way to initialize my Vim

Included .vimrc:  
<https://github.com/amix/vimrc/blob/master/vimrcs/basic.vim>

Included Plugins:
```vim
Plugin 'VundleVim/Vundle.vim' " Plugin manager
" My plugin
" Theme
Plugin 'NLKNguyen/papercolor-theme'
" Auto close brackets
Plugin 'Raimondi/delimitMate'
" File explorer
Plugin 'scrooloose/nerdtree'
```
Others settings:
```vim
" Plugin settings
colorscheme PaperColor
" change to dark if you want to use dark mode
set background=light
" Ctrl+N to toggle nerdtree
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
