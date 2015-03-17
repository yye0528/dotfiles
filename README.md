# dotfiles
configuration files that mostly taken from others.

## dependencies of zsh configuration:

### agnoster theme
to use zsh agnoster theme in Ubuntu, install [solarized](https://github.com/altercation/solarized) color theme first

the font is broken in the most recent version of oh-my-zsh for Ubuntu. Fall back to use the old version of agnoster theme:
```
cd ~/.oh-my-zsh/themes/
git checkout  d6a36b1 agnoster.zsh-theme
```

### zsh syntax highlighter
install and use the zsh syntax highlighter plugin
```
cd ~/.oh-my-zsh/custom/plugins
git clone git://github.com/zsh-users/zsh-syntax-highlighting.git
```
