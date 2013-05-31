dotvim
======
vim script

usage
============
~~~~~
git clone git@github.com:jacky098123/dotvim.git # READ, WRITE
ln -s ~/.vim/vimrc ~/.vimrc
cd ~/.vim
git submodule init
git submodule update
~~~~~



build github repository
===========================

get repository
---------------------
~~~~~~~
git clone git@github.com:jacky098123/dotvim.git # READ, WRITE
git clone git://github.com/jacky098123/dotvim.git # READ
~~~~~~~


get pathogen
-----------------------
~~~~~~~
mkdir -p ~/.vim/autoload ~/.vim/bundle; \
curl -Sso ~/.vim/autoload/pathogen.vim \
    https://raw.github.com/tpope/vim-pathogen/master/autoload/pathogen.vim
~~~~~~~


submodule
---------------------
~~~~~~~
git submodule add  https://github.com/scrooloose/syntastic.git bundle/syntastic
git submodule add  https://github.com/scrooloose/vim-markdown.git bundle/vim-markdown
~~~~~~~

