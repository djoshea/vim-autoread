============
vim-autoread
============

Automatically causes vim to reload files which have been written on disk but not
modified in the buffer since the last write from vim. This enables a file open in
vim to be edited using another application and saved. Upon returning to vim, 
as long as you haven't modified the file since the last change, the file will be
automatically updated to reflect the changes made on disk, as though you had pressed
:e manually.

This is a bundled form of this script_ in order to be fetchable by Vundle_.

.. _script: http://vim.wikia.com/wiki/Have_Vim_check_automatically_if_the_file_has_changed_externally
.. _Vundle: https://github.com/gmarik/vundle


Installation
============

Place in your vim plugins folder or add to your .vimrc::

    Bundle 'djoshea/vim-autoread'
