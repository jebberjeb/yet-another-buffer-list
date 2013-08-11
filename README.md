## Why? 

After trying a few variants of [MiniBufEpl] (http://www.vim.org/scripts/script.php?script_id=159)
and [buftabs] (http://www.vim.org/scripts/script.php?script_id=1664) (both nice
plugins), wanted something

* very simple -- just opens list of bufers in a vsplit
* pure vimscript

## Bindings

* &lt;leader&gt;b - show buffer list
* &lt;enter&gt; - select a buffer from the list (of cursor's row)
* q - close the buffer list
* d - delete the buffer (of cursor's row)

## Installation

Copy buflist.vim to ~/.vim/plugin/
