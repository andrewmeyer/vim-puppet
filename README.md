vim-puppet
==========

Make vim more Puppet friendly!

Provides
--------

* Formatting based on the latest Puppetlabs Style Guide
* Syntax highlighting compatible with puppet 4.x
* Automatic => alignment
  * If you don't like that, add `let g:puppet_align_hashes = 0` to your vimrc.
* Doesn't require a bloated JRE
* Doesn't take minutes to open

Additional useful plugins
-------------------------

* [vim-yardoc](https://github.com/noprompt/vim-yardoc) Syntax coloration for
  YARD tags and directives. It can also colorize the tags and directives in
  puppet files.
* [syntastic](https://github.com/scrooloose/syntastic) plugin for automatic
   syntax checking while in vim.
* [vim-snippets](https://github.com/honza/vim-snippets) is a library of
  snippets for multiple languages, including Puppet. Works with both
  [snipmate](https://github.com/garbas/vim-snipmate) and
  [ultisnips](https://github.com/SirVer/ultisnips).

Installation
------------

With [Vim 8 packages](http://vimhelp.appspot.com/repeat.txt.html#packages):

    git clone https://github.com/rodjek/vim-puppet.git ~/.vim/pack/plugins/start/vim-puppet

With [Pathogen](https://github.com/tpope/vim-pathogen):

If you're using [pathogen](https://github.com/tpope/vim-pathogen) to manage
your vim modules (and if you're not, why aren't you), you can simply add this
as a submodule in your `~/.vim/bundle/` directory.

Testing
-------

Testing is based on vader.vim testing framework, see:
<https://github.com/junegunn/vader.vim> . To run full test suit use
`./test/run-tests.sh`, this will also download vader.vim plugin to project's
folder.

