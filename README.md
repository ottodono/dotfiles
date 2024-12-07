# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Update packages

```
$ sudo apt update
```

### Git

```
$ sudo apt install git
```

### Stow

```
$ sudo apt install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com:ottodono/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```

### Zsh

```
apt install zsh
```

### oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#### zsh-autosuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

#### zsh-syntax-highlighting
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

## Tmux
```
apt install tmux
```

Install Tmux Plugin Manager
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

```
tmux source ~/.config/tmux/tmux.conf
```

### nvim
```
sudo apt install neovim
```

Install Tree Sitter
```
TSInstall java
TSInstall markdown
TSInstall yaml
```
For java gcc is required
```
apt install gcc
````

#### NVChad
```
 git clone -b v2.0 https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim
```


