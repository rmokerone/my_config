MY_CONFIG
===
# 1. VIM

## 1.1 安装

安装nvim
```
brew install neovim
```

修改vim默认设置
```
# vim ~/.zshrc 或 ~/.bashrc
alias vim='nvim'
alias vi='nvim'
```
检查
```
nvim +checkhealth
```

支持python
```
pip install neovim --upgrade
```

安装配置文件
```
# mac命令
ln -s ~/.vim ~/.config/nvim
ln -s ~/.vimrc ~/.config/nvim/init.vim

# linux命令
ln -s ~/.config/nvim ~/.vim
ln -s ~/.config/nvim/init.vim ~/.vimrc 
```

插件配置
```
# 安装插键
:PlugInstall
# 检查状态
:PlugStatus
# 删除插键（需要先将 ~/.config/nvim/init.vim 中注释掉相关插键）
:PlugClean
# 更新插键
: PlugUpdate
# 升级 vim-plug
:PlugUpgrade
```

## 1.2 配置说明

# 2. TMUX

## 2.1 安装

安装配置文件
```
ln -s ~/.tmux.conf ~/.config/tmux/tmux.conf

# linux命令
ln -s ~/.config/tmux/tmux.conf ~/.tmux.conf
```

## 2.2 配置说明

前导符
```
默认 <prefix> 组合键，是 C-b (即Ctrl+b)
```

分屏
```
# 上下
<prefix> + -
# 左右
<prefix> + |
```
