# vim abolish

> Easily search for, substitute, and abbreviate multiple variants of a word
> https://github.com/tpope/vim-abolish

- When you type a word that matches the first param, it will instantly replace it with the second param

:Abolish {despa,sepe}rat{e,es,ed,ing,ely,ion,ions,or}  {despe,sepa}rat{}

- Find and replace multiple versions of similar words (singular, plural)

:%Subvert/facilit{y,ies}/building{,s}/g

- Coerce the currently highlighted word to: MixedCase, camelCase, snake_case, UPPER_CASE, dash-case, dot.case, Title Case, or space case

cr[mcsu-.t ]
