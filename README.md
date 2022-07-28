# vimrc


mkdir -p ~/.vim && touch ~/.vimrc

mkdir -p ~/.vim/bundle

cd  ~/.vim/bundle
git clone https://github.com/gmarik/vundle.git

cd ~
git clone https://github.com/gmarik/vundle.git


-- 执行安装指令
:PluginInstall
