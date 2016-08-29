
cd $HOME

git clone https://github.com/weisd/macvimrc.git

mv .vim .vimbak
mv .vimrc .vimbak
mv .tmux.conf .tmux.conf

ln -sf ./macvimrc/maximum-awesome/vim .vim

ln -sf ./macvimrc/maximum-awesome/vimrc .vimrc

ln -sf ./macvimrc/maximum-awesome/tmux.conf .tmux.conf

