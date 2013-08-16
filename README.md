dotfiles.git
============
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure your `bash` and `emacs` development environment as follows:

```sh
cd $HOME
git clone https://github.com/octavio-orozco2/dotfiles.git
ln -sb dotfiles/.tmux.conf ~
ln -sb dotfiles/.bash_profile ~
ln -sb dotfiles/.bashrc ~
ln -sb dotfiles/.bashrc_custom ~
ln -sb dotfiles/.gitconfig ~
ln -sb dotfiles/.jshintrc ~
ln -sd .vim dotfiles/.vim
```
