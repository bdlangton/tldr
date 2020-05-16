# vim misc

> Miscellaneous vim commands.

- Start a macro stored to "letter" and "commands" are the commands you execute

`q<letter><commands>q`

- Execute a stored macro

`@<letter>`

- Insert a single character while in normal mode and immediately go back to normal mode (custom mapping)

`I<char>`

- Clear the highlighting of the previous search (custom mapping)

`:noh OR Ctrl+z`

- Cycle through previous commands

`: + Ctrl+p`

- Execute a command in the shell

`:!<cmd>`

- Execute the previous command again

`:!!`

- Jump from the use of a variable to its local declaration.

`gd`

- Go to the last place that you edited.

`g;`

- Current filename

`%`

- Repeats the last command.

`.`

- Without argument will show all current mappings.<br>With argument, it’ll show what that key binding is mapped to.<br>You can pass partial argument and it’ll show a list that start with your arg

`:map [<arg>]`

- Show all defined variables

`:let`

- Show the value of the variable name (don’t need to include g: or b: or l: before the variable.

`:let <variable-name>`

- List all color groups

`:hi`

- View registers

`:reg`

- Paste data from a register while in insert mode

`Ctrl+r <reg>`

- Display the path of the current file relative to the current working dir (1+Ctrl+g to do full path)

`Ctrl+g`

- Go to the definition/tag under the cursor.

`Ctrl+]`

- PHP lint on the current file (custom mapping)

`Ctrl+\`

- Autocomplete the current word.

`Ctrl+N`

- The same as Esc with this set: inoremap jk

`jk`
