# Vim Package Managers

## Native Package Management

```
cd ~
mkdir -p ~/.vim/pack/yourpackagename
mkdir ~/.vim/pack/yourpackagename/start
mkdir ~/.vim/pack/yourpackagename/opt
cd ~/.vim/pack/yourpackagename/start
git clone https://github.com/tpope/vim-surround.git
cd ~/.vim/pack/yourpackagename/opt
git clone https://github.com/tpope/vim-endwise
```

`vim-surround` should be auto-loaded to your runtimepath. To enable `vim-endwise`, `packadd vim-endwise` can be added to your `.vimrc` or called.


## Links

* [Vim packages](https://vim-jp.org/vimdoc-en/repeat.html#packages)
* [Vim jobs](https://vim-jp.org/vimdoc-en/channel.html#job-channel-overview)
* [Pathogen](https://github.com/tpope/vim-pathogen)
* [Vundle](https://github.com/VundleVim/Vundle.vim)
* [Vim Plug](https://github.com/junegunn/vim-plug)
* [dein.vim](https://github.com/Shougo/dein.vim)
* [volt](https://github.com/vim-volt/volt)
* [minpac](https://github.com/k-takata/minpac)

## About

This project contains a simple Vagrantfile for spinning up a new Ubuntu 18 box. This is provided as a convenience to allow users to experiment with different packagae managers without having to modify their local environment.

##### Requirements

* [Vagrant](https://www.vagrantup.com/downloads.html)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

```
vagrant up
```
