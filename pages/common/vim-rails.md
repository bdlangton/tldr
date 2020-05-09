# vim rails

> Ruby on Rails power tools
> https://github.com/tpope/vim-rails

- Open a specific controller. Add '!' to the end to create.

`:Econtroller [name]`

- Open a specific view. Add '!' to the end to create.

`:Eview [name]`

- Same as the above two, generally

`:Emodel, :Ehelper, :Ejob, :Emailer, :Emigration, :Etask`

- Open db/schema.rb

`:Eschema`

- Open Gemfile

`:Elib`

- Open application.rb, or if you pass a param it'll open the file for that environment (development, test, etc)

`:Eenvironment`

- Run unit/models/helpers tests

`:Espec, :Eunittest`

- Run functional/controllers/mailers tests

`:Efunctionaltest`

- Run integration/featuers/requests tests

`:Eintegrationtest`
