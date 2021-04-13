# fbcset

### a fbterm color theme setter

**A Primer**

`fbcset` is a simple bash script to help bring life to your dreary fbterm-over-a-tty environment. It allows you to set color themes by feeding it theme files using a very simple syntax and html-like color values for any number of colors at once. No more converting #rrggbb to decimal and crafting escape sequences for days.

**How to Install**

1. `git clone https://github.com/m98blk/fbcset fbcset`
2. That's it

**How to Use**

`fbcset` looks for themes in `$HOME/.fbthemes`. Create this directory and put your theme files in it, where you will then be able to load them from by passing just the filename to `fbcset`. You can also pass explicit paths using the `-f` option. For more information including the theme file format, see the included help by running `fbcset -h`.

**The Boring Stuff**

This program is released under The Unlicense. See the LICENSE file for more information.

**Author:** m98blk
