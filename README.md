## init.vim位置

```shell
~/.config/nvim/init.vim
```



## 安装步骤

#### 1.安装vim-plug



```shell
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

#### 2.依赖安装

```shell
sudo apt install clangd
```

#### 3.安装插件

```shell
:PlugInstall
```

