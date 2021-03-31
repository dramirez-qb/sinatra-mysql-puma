# Sinatra web-app

Sinatra web-app with MySQL Backend.

You should have an existing MySQL-Database to use this app.

## Installation

```console
git clone https://github.com/dxas90/sinatra-mysql-puma.git
cd sinatra-mysql-puma
bundle install
export RACK_ENV=development
rake db:create
rake db:schema:load
bundle exec puma config.ru -C puma.rb
```
