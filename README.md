# Use Ctrl-Z to switch back to Vim

## Installation

### Using zgen

Include the load command in your .zshrc

```
zgen load yuki-ycino/fancy-ctrl-z
zgen save
```

### Using zplug

Load cdd as a plugin in your .zshrc

```
zplug "yuki-ycino/fancy-ctrl-z"
```

### Using Antigen

Bundle cdd in your .zshrc

```
antigen bundle yuki-ycino/fancy-ctrl-z
antigen apply
```

## Settings

Add the following lines to your .zshrc:

```
bindkey '^z' fancy-ctrl-z
```

Show: https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/fancy-ctrl-z/README.md
Source: http://sheerun.net/2014/03/21/how-to-boost-your-vim-productivity/
