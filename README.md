Installation:

    git clone https://github.com/hejersbo/dotfiles.git ~/dotfiles

Create symlinks:

    ln -s ~/dotfiles/vim/vimrc ~/.vimrc
    ln -s ~/dotfiles/vim/gvimrc ~/.gvimrc (optional)
    ln -s ~/dotfiles/tmux/tmux.conf ~/.tmux.conf
    ln -s ~/dotfiles/xmodmap/xmodmap ~/.Xmodmap

Install Vim plugins:

    git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

    launch vim and run :PluginInstall

