## Dotfiles

Notes:
* Terminal colors: [linux](https://github.com/sigurdga/gnome-terminal-colors-solarized).

Basic vim setup:
* First, install vim.
* Clone the repositories & set up links.

        git clone https://github.com/awylie/dotfiles.git ~/dotfiles
        <create symlinks to individual dotfiles>
        git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
        git clone --recursive https://github.com/Valloric/YouCompleteMe.git \
            ~/.vim/bundle/YouCompleteMe

* Note: Certain Vundle plugins have more involved installation steps (eg. YouCompleteMe).
* Install the vim bundles.

        vim +PluginInstall +qall
