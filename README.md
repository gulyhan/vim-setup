# vim-setup
Vim setup files

# Guide

## Remove existing vim files

```
rm -rf ~/.vimrc
rm -rf ~/.vim
```

## Use the .vimrc

Download the .vimrc from this repository.
Edit the .vimrc file and update the settings by typing (in Vim):
```
:source %
```

## Setting up the plugins

Download the vim plugins downloader ([command from this github repository](https://github.com/junegunn/vim-plug))
```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

Install the plugins (in Vim) type:
```
:PlugInstall
```

Download the typescript completer from YouCompleteMe
```
cd ~/.vim/plugged/YouCompleteMe
./install.py --ts-completer
```

# Keymaps

## Windows

Open a files tree window on the left
```
SPACE + pv
```

## Code nagivation
Go to the definition
```
(while having the cursor on the word) gd
```


# Rerefence

[Your first VimRC: How to setup your vim's vimrc](https://youtu.be/n9k9scbTuvQ) from ThePrimeagen
