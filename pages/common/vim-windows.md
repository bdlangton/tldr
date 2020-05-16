# vim windows

> Window functionality in vim.

- Switch to the last opened file

`<leader><leader>`

- Edit another file

`:e filename`

- Split window (windows on top of each other) and load another file

`:split [file]`

- Split window (windows side by side) and load another file

`:vsplit [file]`

- Split window horizontally (w/netrw explorer) (custom mapping)

`<leader>-`

- Split window vertically (w/netrw explorer) (custom mapping)

`<leader>\`

- Split a window horizontally

`ctrl-w ctrl-s OR ctrl-w s`

- Split a window vertically

`ctrl-w ctrl-v OR ctrl-w v`

- Close the current window (keeping others open)

`:q`

- move cursor to another window (cycle)

`ctrl-w ctrl-w OR ctrl-w w`

- Move to other window left/down/up/right

`ctrl-[hjkl]`

- Move the current window left/down/up/right

`ctrl-w [HJKL]`

- Rotate all windows (capital for reverse)

`ctrl-w r OR ctrl-w R`

- Swap the current window with its closest neighbor (custom mapping)

`ctrl-w x OR <leader>{ OR <leader>}`

- maximize current window

`ctrl-w _`

- Make all windows equal size (custom mapping)

`ctrl-w = OR <leader>=`

- Increase height of current window

`ctrl-w +`

- Decrease height of current window

`ctrl-w -`

- Increase or decrease width of current window (if {nr} provided it goes that many spaces, otherwise 1 space)

`ctrl-w {nr}> OR ctrl-w {nr}<`

- Set the current window's height to {nr} number

`z{nr}<CR>`

- Set the current window's height to {nr}, or if {nr} is preceded by +/- it will resize it by that much relative to current height

`:res {nr}`

- Set the current window's width to {nr}, or if {nr} is preceded by +/- it will resize it by that much relative to current width

`:vertical res {nr}`

- Zoom in on the current window like tmux (custom mapping)

`<leader>+`

- same as split, but readonly

`:sview file`

- Open a new empty buffer in a new split

`:new`

- Open a new empty buffer in current window

`:enew`

- Open a new empty buffer in a new vertical split

`:vnew`

- Close current window (custom mapping)

`:hide OR <leader>x`

- Close everything but the current window

`:only`

- Close any preview window

`:pc OR :pclose`
