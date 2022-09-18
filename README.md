# neovim-plugin-termux
How to install vim-plugin in termux

> open termux and type these commands

* 1st
```
apt update -y && apt upgrade -y && apt install git python nodejs neovim wget -y
```
* 2nd
```
mkdir -p .config/nvim
```
* 3rd
```
wget https://raw.githubusercontent.com/brxxlstxrs/VSCode/main/init.vim && mv init.vim .config/nvim
```
* 4th
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
* 5th
```
nvim .config/nvim/init.vim
```

