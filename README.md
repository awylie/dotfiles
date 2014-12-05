## Dotfiles

Basic setup:
* Get the correct version & build of Vim (1)
* Clone the repositories & set up links

        git clone https://github.com/awylie/dotfiles.git ~/dotfiles
        cd ~ && ln -s dotfiles/.vimrc .vimrc
        git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
        git clone --recursive https://github.com/Valloric/YouCompleteMe.git \
            ~/.vim/bundle/YouCompleteMe


* [Build YouCompleteMe](https://github.com/Valloric/YouCompleteMe#ubuntu-linux-x64-super-quick-installation)
* Install terminal colors ([linux](https://github.com/sigurdga/gnome-terminal-colors-solarized)/[mac](https://github.com/tomislav/osx-terminal.app-colors-solarized))

* Install the vim bundles

        vim +PluginInstall +qall

Notes:

1.  [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) requires Vim 7.3.584 (or greater) with python2 support.  On Mac OS X I've installed MacVim with brew and aliased `alias vim='mvim -v'`.  All other steps work without changes.
