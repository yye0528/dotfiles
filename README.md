# dotfiles
configuration files that mostly taken from others.

## zsh

### zsh installation

```
sudo apt-get install zsh
```

### oh-my-zsh 

via curl

```
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
```
via wget

```
wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O - | sh
```

### change default shell

```
chsh -s /usr/bin/zsh $USER
```

### zsh themes
The plain powerline theme: [powerline](https://github.com/carlcarl/powerline-zsh)

Solarized terminal color theme for : [solarized color theme for genome terminal](https://github.com/Anthony25/gnome-terminal-colors-solarized)

Poweverline fonts: [Patched Powerline fonts](https://github.com/powerline/fonts). 

Fonts can be changed in terminal profile preferences. The 12px "Ubuntu Mono Derivative Powerline" works fine.

### zsh syntax highlighter
install and use the zsh syntax highlighter plugin
```
cd ~/.oh-my-zsh/custom/plugins
git clone git://github.com/zsh-users/zsh-syntax-highlighting.git
```


