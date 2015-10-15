# Tung Ha's dotfiles

~~~sh
git clone https://github.com/tunght13488/dotfiles.git $HOME/dotfiles
git clone https://github.com/tmux-plugins/tpm $HOME/.tmux/plugins/tpm
cd $HOME/dotfiles
git submodule init
git submodule update
stow git
stow vim
stow tmux
stow other
vim +PluginInstall +qall
~~~
