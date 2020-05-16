# vim files dir

> Files and directories.

- Reload current file

`:e!`

- Insert contents of file into the current buffer

`:r [file]`

- Echo current working directory

`:pwd`

- Change current working directory

`:cd [dir]`

- Change the working directory for just the current window

`:lcd [dir]`

- Prints out the current file’s full directory path. Useful if you want to do something like ":r file", but you’re in a project so the cwd is the project’s dir. That means you need to use %:h:p to easily get to the other file. Example: ":r %:h:p/OtherFile.php"

`%:h:p OR %:h (I think :r only uses this, no ":p")`
