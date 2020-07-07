# vimrc

```bash
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
- #### **EDIT ~/.vimrc**
```markdown
set nocompatible
filetype off
"Add Vundle to runtime path
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()
Plugin 'gmarik/Vundle.vim'
"""""""""""""""""""""""
"" Add new plugins here
"""""""""""""""""""""""

"""""""""""""""""""""""
"" End of plugin list
"""""""""""""""""""""""
call vundle#end()
filetype plugin indent on 
```
