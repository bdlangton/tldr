# vim ale

> Check syntax in Vim asynchronously and fix files
> https://github.com/dense-analysis/ale

- Show ALE config info

`:ALEInfo`

- Manually run a fix on the current file (useful when I don't have automatic fixers for a filetype)

`:ALEFix <fixer>`

- Shows you a list of potential fixers for the filetype

`:ALEFixSuggest`

- Show detailed info about the error currently highlighted (custom mapping)

`:ALEDetail OR <leader>i`

- Enable ALE

`:ALEEnable`

- Disable ALE

`:ALEDisable`
