# Welcome to CallumS005's GitHub.

![callums005's profile picture](https://avatars.githubusercontent.com/u/59845571?s=400&u=50d0164862bc1167a8573b440b12c25beec7feaa&v=4)

My name is Callum and I'm studying computer science.

I'm currently working on a 2D Game Engine in C++. I'm also in the process of migrating to GitLab.

## My NeoVim Config

```vim
:set number
:set autoindent
:set tabstop=4
:set shiftwidth=4
:set smarttab
:set softtabstop=4
:set mouse=a

call plug#begin()

Plug 'https://github.com/vim-airline/vim-airline'
Plug 'https://github.com/preservim/nerdtree'
Plug 'https://github.com/tpope/vim-surround'
Plug 'https://github.com/tpope/vim-commentary'
Plug 'https://github.com/ap/vim-css-color'
" Plug 'https://github.com/rafi/awesome-vim-colorschemes'
Plug 'https://github.com/drewtempelmeyer/palenight.vim'
Plug 'https://github.com/ryanoasis/vim-devicons'
Plug 'https://github.com/tc50cal/vim-terminal'
Plug 'https://github.com/terryma/vim-multiple-cursors'
Plug 'https://github.com/preservim/tagbar'
Plug 'https://github.com/luochen1990/rainbow'
Plug 'https://github.com/neoclide/coc.nvim'

call plug#end()

:colorscheme palenight

nnoremap <c-z> <nop>

:set nobackup
:set nowritebackup



" :CocInstall coc-python

nnoremap <C-f> :NERDTreeFocus<CR>
nnoremap <C-n> :NERDTree<CR>
nnoremap <C-e> :NERDTreeToggle<CR>
nnoremap <C-t> :TerminalSplit bash<CR>
nmap <F8> :TagbarToggle<CR>

:set completeopt -=preview
inoremap <expr> <Tab> pumvisible() ? coc#_select_confirm() : "<Tab>"
```

## Links
- [My Website](https://callums005.net)
- [GitLab](https://gitlab.com/CallumS005)
