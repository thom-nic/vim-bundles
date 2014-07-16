# Vim Bundles

This is just a collection of submodules to existing Vim plugins that I like 
to use.  Sort of like dotfiles.  

Plugins are loaded using [Pathogen](runtime bundle/vim-pathogen/autoload/pathogen.vim).  

In fact, Pathogen is itself included as a submodule which means my `.vimrc` 
looks like this:

```
runtime bundle/vim-pathogen/autoload/pathogen.vim
execute pathogen#infect()
```
