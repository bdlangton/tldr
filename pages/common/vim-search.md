# vim search

> Searching in vim.

- search forward or backward for pattern

`/pattern OR ?pattern`

- repeat search in same direction or opposite direction

`n or N`

- Search for word currently under cursor (forward or backward)

`* OR #`

- Go to the next or previous character in the line

`f OR F`

- Go to the 3rd occurence of the character

`3f`

- Go to one character before the next occurence of the next character, or one
  after the previous occurence

`t or T`

- Repeat last f/F/t/T movement in same direction or opposite direction

`; OR ,`

- Find each occurrence of 'foo' (in all lines), and replace it with 'bar'. Remove the ‘%’ to only search the current line.

`:%s/foo/bar/g OR Options after last “/”: OR g - global OR c - confirmation OR e - suppress errors`

- Change only whole words exactly matching 'foo' to 'bar'; ask for confirmation.

`:%s/\<foo\>/bar/gc`

- Find and replace in all buffers and save the buffer if changes were made

`:bufdo %s/pattern/replace/ge | update`
