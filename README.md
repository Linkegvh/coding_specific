# The below is what I have done to get my vim plug-ins. 

## The screenshot is what the page of the original bash file. I will later update what i have done to change my terminal color and stuff here.


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
