# Vim

I use neovim as my main text editor, and vim elsewhere.

## Dependencies

- `vim` - If you're reading this, you probably already know what vim is
- `neovim` - An improved version of vim (cursor modes, sane defaults, etc.)
- `wal` - Changing color schemes support
- `fzf` - Fuzzy search support
- `ripgrep` - Jump between lines in files
- `git` - Git diff support
- Any other features you want to use (e.g. TeX support with `texlive`)

## Installation

```sh
make package=vim
```

## Usage

I use [vim-plug][vim-plug] as my plugin manager of choice. Install it, then run:

```
vim +PlugInstall +qall
```

Now you can use my vim config with all the plugins installed!

[vim-plug]: https://github.com/junegunn/vim-plug