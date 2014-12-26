### My dotfiles

__Installation:__

If you already have [__git__](http://git-scm.com/) installed, you can run the following commands in your prompt:
```bash
git clone https://github.com/georgijd/dotfiles.git ~/dotfiles
cd ~/dotfiles
. make_symlinks.sh
```

If you want, you can run the following command to automatically setup Vim, Vundle and all Vundle Plugins:
```bash
. setup_vim.sh
```

In case you don't have [__git__](http://git-scm.com/) installed, just download the [ZIP file](https://github.com/georgijd/dotfiles/archive/master.zip) for this project and unzip it to ~/dotfiles. Then:
```bash
cd ~/dotfiles
. make_symlinks.sh
. setup_vim.sh
```

> Note that __setup_vim.sh__ will also try to install Git on your machine.

