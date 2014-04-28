==========
VIM RENAME
==========

A command and function that basically does a ":saveas <newfile>" then removes the old filename on the disk.

This plugin is forked from::

    http://www.vim.org/scripts/script.php?script_id=2724

With only one fix so far: allows to rename files even file path has spaces.

Simple usage
------------

When you editing a file and you need to rename it, in command mode execute::

    :Rename new_file_name.txt

VIM-BUNDLE
----------

This plugin should work with VIM bundle, so checkout this repo in bundle folder.

If you are not using VIM bundle, then make sure you have the same file in your VIM plugin directory as this repo has.

Authors
-------

Original author Christian J. Robinson, contributed by Manni Heumann and Remigijus Jarmalavičius.
