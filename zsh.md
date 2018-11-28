# zsh

## Install iTerm
download it from https://www.iterm2.com/version3.html

## Install zsh
``` shell
brew install zsh zsh-completions
```

### Change zsh as your default shell
``` shell
chsh -s /bin/zsh
```

test:
``` shell
echo $SHELL
```
you should see ```/bin/zsh```

## Install oh-my-zsh
``` shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Configure oh-my-zsh
### Theme
all available themes: https://github.com/robbyrussell/oh-my-zsh/wiki/themes

edit ~/.zshrc

``` shell
ZSH_THEME="avit"
```

### Plugins

all available plugins: https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins

#### [auto-complete](http://mimosa-pudica.net/zsh-incremental.html)
download:
``` shell
$ wget http://mimosa-pudica.net/src/incr-0.2.zsh
```

put into oh-my-zsh plugins folder

edit ~/.zshrc, add following line at bottom
``` shell
source ~/.oh-my-zsh/plugins/incr/incr*.zsh
```

#### others:
encode64
extract
git
osx
vscode
z
