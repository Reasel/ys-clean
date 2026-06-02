# ys-clean

A minimal fork of the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) oh-my-zsh theme with the clock removed and a cleaner dirty indicator (`x` instead of a symbol).

## Prerequisites

- [oh-my-zsh](https://ohmyz.sh/) must be installed (`~/.oh-my-zsh/` exists)

## Install

**1. Download the theme file into your oh-my-zsh custom themes directory:**

```sh
curl -o "${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/ys-clean.zsh-theme" \
  https://raw.githubusercontent.com/Reasel/ys-clean/main/ys-clean.zsh-theme
```

**2. Set the theme in `~/.zshrc`:**

```sh
# Find and replace the ZSH_THEME line:
sed -i 's/^ZSH_THEME=.*/ZSH_THEME="ys-clean"/' ~/.zshrc
```

Or edit `~/.zshrc` manually and set:

```sh
ZSH_THEME="ys-clean"
```

**3. Reload the shell:**

```sh
source ~/.zshrc
```
