dotvim
======

vim script

build github repository
===========================

get repository
---------------------
git clone git@github.com:jacky098123/dotvim.git
OR
git clone git://github.com/jacky098123/dotvim.git


get pathogen
-----------------------
~~~~~~~
mkdir -p ~/.vim/autoload ~/.vim/bundle; \
curl -Sso ~/.vim/autoload/pathogen.vim \
    https://raw.github.com/tpope/vim-pathogen/master/autoload/pathogen.vim
~~~~~~~


submodule
---------------------
git submodule add  https://github.com/scrooloose/syntastic.git bundle/syntastic
git submodule add  https://github.com/scrooloose/vim-markdown.git bundle/vim-markdown
