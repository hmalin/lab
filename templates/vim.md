# Vim Guide 

## Modes
- `i` - Insert mode
- `v` - Visual mode
- `V` - Visual line mode
- `Ctrl + v` - Visual block mode
- `Esc` - Normal mode

## Navigation
- `h` - Move left
- `l` - Move right
- `j` - Move down
- `k` - Move up
- `w` - Jump to next word
- `b` - Jump to previous word
- `0` - Start of line
- `^` - First non-blank character of line
- `$` - End of line
- `gg` - Beginning of file
- `G` - End of file
- `Ctrl + d` - Half-page down
- `Ctrl + u` - Half-page up

## Editing
- `x` - Delete character under cursor
- `dd` - Delete current line
- `yy` - Copy (yank) current line
- `p` - Paste after cursor
- `P` - Paste before cursor
- `r<char>` - Replace character under cursor
- `ciw` - Change inner word
- `cw` - Change word
- `cc` - Change entire line
- `u` - Undo
- `Ctrl + r` - Redo

## Searching
- `/pattern` - Search forward for `pattern`
- `?pattern` - Search backward for `pattern`
- `n` - Repeat last search forward
- `N` - Repeat last search backward

## Saving and Exiting
- `:w` - Save
- `:q` - Quit
- `:wq` or `ZZ` - Save and quit
- `:q!` - Quit without saving

## Buffers and Windows
- `:bn` - Next buffer
- `:bp` - Previous buffer
- `:bd` - Close buffer
- `:split` - Horizontal split
- `:vsplit` - Vertical split
- `Ctrl + w w` - Switch windows

## Miscellaneous
- `.` - Repeat last command
- `:%s/old/new/g` - Replace all `old` with `new`
- `:set number` - Show line numbers
- `:set nohlsearch` - Remove search highlight

