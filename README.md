# zsh-tmux-complete

This is a copy of the script found [here][1] and [here][2], packaged as a zsh plugin to be used with your favorite zsh plugin manager.

[1]: https://gist.github.com/blueyed/6856354
[2]: http://blog.plenz.com/2012-01/zsh-complete-words-from-tmux-pane.html
[3]: http://zsh.sourceforge.net/
[4]: https://github.com/tmux/tmux/wiki

## Requirements

* [ZSH][3] >= 4.3.0
* [tmux][4]

## Install

### antigen

    antigen bundle twang817/zsh-tmux-complete

### zgen

    zgen load twang817/zsh-tmux-complete
    
### antibody

    antibody bundle twang817/zsh-tmux-complete
    
## Usage

This script allows you to complete words from the current tmux pane.  The plugin exposes two ZLE widgets that you can bind to:

```
bindkey '^X^X' tmux-pane-words-prefix
bindkey '^Xt' tmux-pane-words-anywhere
```
