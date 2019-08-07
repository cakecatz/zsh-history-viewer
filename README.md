# zsh-history-viewer

## Required

- [fzf](https://github.com/junegunn/fzf)

## Install

Install by your favorite plugin manager.

### antibody

antibody bundle cakecatz/zsh-history-viewer

## Usage

Add code to ~/.zshrc for shortcut key like this.

```zsh
zle -N history-viewer
bindkey '^r' history-viewer # ctrl + r
```
