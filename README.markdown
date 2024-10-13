# vim-vimhints

my hints for vim, written to be highlighted by (but not really indexed/searched by) the helpfile system

usage:
  :h vimhints       Opens the vimhints file at the top, in a readonly help buffer.
                    From there, you can search for stuff like normal.

maybe one day i'll write more of a plugin for this, so that it works more like my bash hints program, but for now, i'll make do with a helpfile

# Installation

To install, use a plugin manager or use Vim's built-in package support (see `:h packages`).

(If installing manually or with Vim's package support, be sure to run `:helptags ALL` after installation so that `:h vimhints` will work.)

You may also wish to symlink the main help file (doc/vimhints.txt) to somewhere handy, like your root directory.
