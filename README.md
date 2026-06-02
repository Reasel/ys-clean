# ys-clean

A minimal fork of the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) oh-my-zsh theme with the clock removed and a cleaner dirty indicator (`x` instead of a symbol).

## Install

### oh-my-zsh custom theme

```sh
curl -o "${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/ys-clean.zsh-theme" \
  https://raw.githubusercontent.com/Reasel/ys-clean/main/ys-clean.zsh-theme
```

Then set in `~/.zshrc`:

```sh
ZSH_THEME="ys-clean"
```
