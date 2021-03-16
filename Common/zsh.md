# Zsh
Zsh shell with Starship

## Install

```bash
dnf install git zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## `.zshrc`
```bash
export ZSH="/home/admin/.oh-my-zsh"
plugins=(git)
source $ZSH/oh-my-zsh.sh
eval "$(starship init zsh)"
```

## Change shell
Type `chsh` and choose `/bin/zsh`.
