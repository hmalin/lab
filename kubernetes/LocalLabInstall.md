#### Install brew (macos or linux)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


#### Install Rancher desktop 

```shell
brew install rancher-desktop
```

##### Alternatively, run the installer 

https://github.com/rancher-sandbox/rancher-desktop/releases 


#### Install kubectl & k9s 
```shell
brew install kubectl k9s 
```


# .bashrc

Set up .bashrc for kubectl completion by adding the following:

```
alias k='kubectl'

source /etc/bash_completion # not needed on macos

source <(kubectl completion bash)

complete -o default -F __start_kubectl k
```

# .vimrc

basic .vimrc for YAML editing:

```
" Ensure Vim uses filetype plugins
filetype plugin on

" Enable indentation
filetype indent on

" Set the default indentation to 2 spaces for all files
set tabstop=2
set softtabstop=2
set shiftwidth=2
set expandtab

" Highlight trailing whitespace in all files
autocmd BufRead,BufNewFile * match Error /\s\+$/

" Enable auto-indentation
set autoindent

" Turn on syntax highlighting
syntax on

" Set backspace so it acts more intuitively
set backspace=indent,eol,start
```
