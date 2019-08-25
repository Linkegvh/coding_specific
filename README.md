# The below is what I have done to get my vim plug-ins. 

## The screenshot is what the page of the original bash file. 


miaocorgi@Ding:~$ vim .vimrc

set nocompatible
filetype off
set rtp+=~/.vim/bundle/Vundle.vim

call vundle#begin()

        Plugin 'VundleVim/Vundle.vim'

        Plugin 'git://git.wincent.com/command-t.git'

        Plugin 'file:///home/gmarik/path/to/plugin'

        Plugin 'rstacruz/sparkup', {'rtp': 'vim/'}

        Plugin 'scrooloose/syntastic'

        Plugin 'junegunn/fzf'

        Plugin 'vim-airline/vim-airline'

        Plugin 'dracula/dracula-theme'
call vundle#end()
 NORMAL  .vimrc                                     vim    4% ☰    1/24 ㏑ :  1 
".vimrc" 24L, 424C


## This is what I have changed to make my terminal highlight some of the things that I want to highlight.

miaocorgi@Ding:~$ vim .bash_profile

export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "

export CLICOLOR=1

export LSCOLORS=ExFxBxDxCxegedabagacad

alias ls='ls -GFh'

# Setting PATH for Python 3.7
# The original version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/3.7/bin:${PATH}"
export PATH

# added by Anaconda3 5.1.0 installer
export PATH="/anaconda3/bin:$PATH"
~                                                                               
~                                                                               
~                                                                               
~                                                                               
 NORMAL  .bash_profile                               sh    6% ☰    1/15 ㏑ :  1 
".bash_profile" 15L, 403C