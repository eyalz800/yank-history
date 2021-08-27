historize vim yanks and allow to search and paste from history based on FZF

## demo

![demo](https://raw.githubusercontent.com/yazgoo/yank-history/gif/YankHistorySmall.gif)

## requirements

You need [ripgrep (rg)](https://github.com/BurntSushi/ripgrep) installed.

You also need [fzf](https://github.com/junegunn/fzf.vim), which you can install via vimplug:

```vim
Plug 'junegunn/fzf', { 'do': { -> fzf#install() } }
Plug 'junegunn/fzf.vim'
```

## installation

Via vimplug:

```vim
Plug 'yazgoo/yank-history'
```

## usage

See [documentation](doc/yank-history.txt).

An example of usage is:

```vim
nmap <space>h :YankHistoryRgPaste 
```

Just input a pattern to search on vim prompt, then select the yank you want to paste.
