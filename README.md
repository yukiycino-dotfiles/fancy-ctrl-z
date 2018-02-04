# Use Ctrl-Z to switch back to Vim

## Installation

### Using zgen

Include the load command in your .zshrc

```
zgen load yukiycino-dotfiles/fancy-ctrl-z
```

### Using zplug

Load cdd as a plugin in your .zshrc

```
zplug "yukiycino-dotfiles/fancy-ctrl-z"
```

### Using Antigen

Bundle cdd in your .zshrc

```
antigen bundle yukiycino-dotfiles/fancy-ctrl-z
```

## Settings

Add the following lines to your .zshrc:

```
bindkey '^z' fancy-ctrl-z
```

Show: https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/fancy-ctrl-z/README.md

Source: http://sheerun.net/2014/03/21/how-to-boost-your-vim-productivity/
