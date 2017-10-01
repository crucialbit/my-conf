## Install Vundle & ~/.vimrc
```terminal
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
wget https://raw.githubusercontent.com/crucialbit/vimrc/master/my.vim -O ~/.vimrc
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
