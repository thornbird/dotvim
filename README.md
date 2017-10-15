dotvim files
==========================
This is refrence from (Jing's dotvim)[https://github.com/thornbird/dotvim]

Installation
------------

```
git clone https://github.com/qqshfox/dotvim.git ~/.vim
cd ~/.vim
make install
```

Dependencies
------------

* YouCompleteMe requires vim is larger than 7.3.584, but mac original vim is 7.3
* Install macvim via `brew install macvim` and the command is `mvim`
* Ruby and Vim 7.3 with ruby support (+ruby) (optional): Command-T and Lusty need these
* Install hg through brew `brew install hg`

Updating
--------

```
git pull
make update
```

Some plugins need
-----------------

* [powerline](https://github.com/Lokaltog/powerline) for vim-powerline
* ack for ack.vim
* Exuberant Ctags 5.8 for AutoTag and Tagbar
* Exuberant Ctags head for Tagbar with Objective-C
* Git for vim-fugitive, gundo.vim and git-grep-vim
* Patched font for vim-powerline
* Erlang and rebar for vim-rebar
* RVM for vim-rvm
* virtualenv for vim-virtualenv
* Erlang for vimerl
* R & [VimCom](https://github.com/jalvesaq/VimCom.git) for Vim-R-Plugin

Configuration of alias vim
------

Put below in your shell shell rc file:
* alias vi='mvim -v'
* alias vim='mvim -v'
* export EDITOR='mvim -v'

Notice
------

* You should check whether the current ruby matches the vim before `make install`, or vim will crash when you use Command-T.
* The latest works in EI Captian Mac.
