# vim surround

> Quoting/parenthesizing made simple
> https://github.com/tpope/vim-surround

- Change the surround of '[find]' with '[replace]' (ex: cs'")

`cs\[find\][replace]`

- Remove the '[char]' surround and don't replace with anything

`ds[char]`

- Surround visually selected block with brackets

`SB`

- Select block of code, surround it with brackets and enter insert mode to add your conditional (if/while/etc)

`Vj%SBi`
