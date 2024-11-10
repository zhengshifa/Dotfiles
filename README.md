mkdir -p ~/.dotfiles
cd ~/.dotfiles
git init


ln -s ~/.dotfiles/.bashrc ~/.bashrc
ln -s ~/.dotfiles/.vimrc ~/.vimrc




示例 .bashrc 配置：

bash
复制代码
# .bashrc
export PATH="$HOME/bin:$PATH"
alias ll="ls -la"
PS1="[\u@\h \W]\$ "
.vimrc: Vim 编辑器的配置文件，配置键绑定、主题、插件等。

示例 .vimrc 配置：

vim
复制代码
" .vimrc
set number
syntax on
set tabstop=4
set shiftwidth=4
set expandtab
.gitconfig: Git 的配置文件，用于设置用户信息、别名、编辑器等。

示例 .gitconfig 配置：

ini
复制代码
[user]
  name = Your Name
  email = your.email@example.com
[core]
  editor = vim
[alias]
  co = checkout
  br = branch