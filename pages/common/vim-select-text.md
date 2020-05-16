# vim select cut copy paste text

> Selecting and cut/copy/paste text.

- Enter visual select by char

`v`

- Enter visual select by line

`V`

- Select block of code + conditional (example: entire 'if' block)

`Vj%`

- In visual: yank selected text

`y`

- Yank current line

`yy`

- Yank from cursor to beginning of next word

`yw`

- Yank line to system clipboard

`"+yy`

- Go to first line and yank to the last line (yank entire file) to system clipboard

`gg"+yG`

- Yank to register (typically "0, "1, etc)

`[register]y`

- Yank inside paragraph

`yip`

- Yank sentence

`yas`

- Yank inside symbol (can be [ { ( < " ')

`yi[symbol]`

- Yank around symbol (including symbol) (can be [ { ( < " ')

`ya[symbol]`

- Paste text

`p`

- Paste text before the cursor

`P`

- Paste from register (typically "0, "1, etc)

`[register]p`

- Insert mode: paste text

`Ctrl+r[register]`
