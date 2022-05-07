## init.vim位置

```shell
~/.config/nvim/init.vim
```



## 安装步骤

#### 1.依赖安装

```shell
sudo apt-get install python-dev python-pip python3-dev python3-pip pip clangd ccls universal-ctags
sudo add-apt-repository ppa:neovim-ppa/stable
sudo apt-get update
sudo apt-get install neovim
```

#### 2.安装vim-plug

```shell
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.'
```

#### 3.复制init.vim到指定位置

```shell
cp init.vim ~/.config/nvim/init.vim
```

#### 3.安装插件

```shell
:PlugInstall
```

