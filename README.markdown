MacroEditor
============

Vim Macros are awesome. But it's hard to get it right on the first try.
MacroEditor is a simple vim plugin that allow you to edit your macros
in a split window. And save it back easily when you are done.

MacroEditor only defines one command: `MacroEdit`

![demo image](https://raw.githubusercontent.com/dohsimpson/vim-macroeditor/master/demo1.png)

Quick Start
-----------

Say if you want to edit your macro in register `q`, you can call:

    :MacroEdit q

A split window will open at the top for editing. When you are done editing,
save and close the window by calling:

    :wq

If you want to discard this edit, simply call:

    :q!

Enjoy vimming!

Installation
------------

To install with [pathogen.vim](https://github.com/tpope/vim-pathogen):

    cd ~/.vim/bundle
    git clone https://github.com/dohsimpson/vim-macroeditor

License
-------

MIT license
