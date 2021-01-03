# vim setting

## how to set vim

first, install ctags for Tagbar plugin

``` shell
$cd
$sudo apt install universal-ctags
```

second, clone this repo

``` shell
$git clone https://github.com/GyeongHoKim/.vim.git
```

third, download Vundle for Plugin

``` shell
$git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

third, move vimrc file & download vim plugins

``` shell
$mv ./.vim/.vimrc ./.vimrc
$vim .vimrc
```

(after pop-up of .vimrc, enter followings~)

``` shell
:PluginInstall
```

if it does not work, then

``` shell
:wq
```

and repeat `:PluginInstall` again

## how to copy vim from local clipboard through ssh

not yet.