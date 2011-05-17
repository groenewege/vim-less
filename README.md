# VIM-LESS #

This vim bundle adds syntax highlighting for the dynamic stylesheet language [LESS](http://lesscss.org).

## Installing and Using ##

1. Install [pathogen](http://www.vim.org/scripts/script.php?script_id=2332) into `~/.vim/autoload/` and add the
   following line to your `~/.vimrc`:

        call pathogen#runtime_append_all_bundles()

     Be aware that it must be added before any `filetype plugin indent on`
     lines according to the install page.

2. Create, and change into, the `~/.vim/bundle/` directory:

        $ mkdir -p ~/.vim/bundle
        $ cd ~/.vim/bundle

3. Make a clone of the `vim-less` repository:

        $ git clone https://github.com/groenewege/vim-less

That's it. Pathogen should handle the rest. Opening a file with a `.less`
extension will load everything.

## Credits ##

Inspiration from [vim-haml](https://github.com/tpope/vim-haml), 
[scss-syntax.vim](https://github.com/cakebaker/scss-syntax.vim) and
[vim-less](https://github.com/lunaru/vim-less)
