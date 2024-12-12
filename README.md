This are the files used to setup a development environment for myself.
In particular, this will include Vim config files, as well as instructions
for setting up my Vim plugins.

## Setup

I use Vundle as my plugin manager for Vim, so use the following to install
Vundle:

```git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim```

After installing Vundle, install the other plugins listed in my .vimrc.

*Note: YouCompleteMe is unable to be installed on MacOS's vim since it lacks
python support*

### Installing YouCompleteMe

* Note: I have installed this on MacOS, but it was an annoying and painful
process, where I was dealing with SSL authentication issues. The below guide
therefore is **not** for MacOS*

To install YouCompleteMe, open vim and enter the following:

```:PluginInstall```

Once this has been done, navigate to ~/.vim/bundle/YouCompleteMe and 

```./install.py --clangd-completer --verbose```

