1. 拷贝该目录下的.vimrc文件到用户目录下～/

2. 创建vim需要的插件目录，并下载插件管理工具Vundle
mkdir -p ~/.vim/bundle
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

3. 使用插件管理工具安装各种插件
在vim命令行执行
VundleInstall
