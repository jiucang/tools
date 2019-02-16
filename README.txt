1. Install zsh
#sudo apt-get install zsh

2. Install VIM8.0
#sudo apt-get install vim

3. Install tmux
#sudo apt-get install tmux

4. Install vim bundle
#git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
#cp vimrc ~/.vimrc
#cp bundles.vim ~/.bundles.vim
Change one first line for .vimrc:
+source ~/.vim/bundle/Vundle.vim
#vim -> :BundleInstall

5. Install oh-my-zsh
#sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

6. Config for tmux
#cp tmux.conf ~/.tmux.conf
#sudo apt-get install tmuxinator
#tmuxinator delete dev
#tmuxinator new dev
#cp tmuxinator_dev.txt ~/.tmuxinator/dev.yml

7. Config for bash
#cp bashrc ~/.bashrc
