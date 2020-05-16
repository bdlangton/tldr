# vim drush

> Custom drush commands.
> Each drush command will use a drush alias if provided (per session) using <leader>dsa.

- drush cr

`<Leader>dcc`

- drush updb -y

`<Leader>dud`

- drush uli

`<Leader>dul`

- drush cex sync -y

`<Leader>dce`

- drush cim sync -y

`<Leader>dci`

- drush watchdog-show

`<Leader>dwd`

- drush en (prompts for module name)

`<Leader>dmi`

- drush pmu -y (prompts for module name)

`<Leader>dmu`

- Prompts to set a drush alias that will be used for future commands

`<Leader>dsa`

- Run any drush command (it'll fill in "drush @alias" for you)

`<Leader>drc`
