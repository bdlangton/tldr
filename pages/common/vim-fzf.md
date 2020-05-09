# vim fzf

> Note: to save multiple results so that you don't have to repeat the same
> search over and over, use Alt-a to select all results then hit Enter on one of
> them. The selected results will display in the quickfix window. You can cycle
> through the results using unimpaired shortcuts like [q and ]q.
> https://github.com/junegunn/fzf.vim/

- Search content in current project using Ag (custom mapping):

`<Leader>a OR :Ag`

- Search content in specific directory (defaults to current dir) using Ag (custom mapping)

`<Leader>A or :Ag`

- Search specific directories for backend/modules (Ab), frontend/themes (Af), or vendor dir (Av). At the root of the project git repo you have to add .vimrc file that defines: let g:backend_dir="modules/custom" and let g:frontend_dir="themes/custom" and let g:vendor_dir="vendor" since each project can have a different directory structure. (custom mapping)

`<leader>Ab OR <leader>Am, <leader>Af OR <leader>At, <leader>Av`

- Search files in current project (custom mapping)

`<leader>f OR :Files`

- Search files in specific directory (defaults to current dir) (custom mapping)

`<leader>F OR :Files`

- Exactly like the custom mappings for A<x>  but these ones will search for files (custom mapping)

`<leader>Fb OR <leader>Fm, <leaader>Ff OR <leader>Ft, <leader>Fv`

- Search buffers (custom mapping)

`<Leader>b OR :Buffers`

- Search tags in current buffer (custom mapping)

`<leader>t OR :BTags`

- Search tags in project (custom mapping)

`<leader>T OR :Tags`

- Search git files

`:GFiles`

- Search lines in current buffer (custom mapping)

`<leader>l OR :BLines`

- Search lines in loaded buffers (custom mapping)

`<leader>L OR :Lines`

- Search git commits (custom mapping). Selecting a commit will load the diff in a buffer.

`<leader>g OR :Commits`

- Search available snippets

`:Snippets`

- Search available normal mode mappings

`:Maps`

- Search filetypes and select one to change the filetype of the current file

`:Filetypes`

- Select all options in the fzf search (Available for :Ag)

`<alt>-a`

- Select the highlighted option in the fzf search and move the highlighted result up one line

`<tab>`

- Select the highlighted option in the fzf search and move the highlighted result down one line

`<shift>-<tab>`
