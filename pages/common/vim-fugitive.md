# vim fugitive

> A Git wrapper so awesome, it should be illegal
> https://github.com/tpope/vim-fugitive/
> https://paper.dropbox.com/doc/Vim-Commands-IuEFxRoL9RC7jwMzabhEl#:uid=780587427746588282143009&h2=Fugitive

- Performs a git diff in a split: index file on the left, working copy on the right (see paper doc for more info)

`:Gdiff (custom) OR :Gdiffsplit OR :Gd (custom) OR <leader>gd (custom)`

- Turn off git diff splits

`:Gdiffoff OR :Gdo OR <leader>gdo`

- git blame (see paper doc for more info)

`:Gblame`

- Runs an interactive view of the status (see paper doc for more info)

`:Gstatus OR :G OR :20Gstatus (keep height to 20 lines)`

- Loads all diffs into quickfix list (each hunk gets an entry). Add '-y' to invoke git diff and load a diff split for each file into new tabs.

`:Git difftool [args] OR :Gdt (custom - runs :Git difftool -y) OR <leader>gdt (custom - runs :Git difftool -y)`

- Like difftool but targets merge conflicts.

`:Git mergetool [args] OR :Gmt (custom - runs :Git mergetool -y) OR <leader>gmt (custom - runs :Git mergetool -y)`

- Run any arbitrary git command

`:Git`

- Write the current file to the index (stage)

`:Gwrite`

- Perform a git checkout on the current file and reloads the buffer

`:Gread`

- Git move (and renames the buffer). Paths are relative to current file’s directory unless you add a “/” before the path, then it’s the root of the git repo.

`:Gmove <file> <newname>`

- Removes the file from the repo and wipes out the buffer.

`:Gremove`

- Pulls up a git commit buffer in a new split in vim. Pros of doing this within current vim session is autocomplete (functions, etc) will be available to you as you type the message.

`:Gcommit`

- Take you to the current version of the file

`:Gedit OR :Gedit :0`

- Edit a sha, which can be a tree, commit, blob or tag (see paper doc for more
  info). Hint: Can go to edit a commit by opening fzf commit search (<leader>g) and clicking Enter on a commit.

`:Gedit <sha>`

- Edit a file from another branch (or another sha). Autocompletion works for the branch and path.

`:Gedit <branch>:<path-to-file>`

- Like Gedit, but opens the file in a split

`:Gsplit OR :Gvsplit`

- Load all commits that touched the current file. The list of commits is in the quickfix window and can cycle through them using ]q or :cnext (and [q or :cprev). See paper doc for more info.

`:0Glog`

- Load all ancestral commit buffers into quickfix (see paper doc for more info)

`:Glog —`

- Git grep wrapper

`:Ggrep <search-text> [<branch/sha>]`
