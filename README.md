# BuhBox

### steps for create project:

Ruby on rails project

```sh
rails new buhbox —database=postgresql —webpack=react
```

create db default SQLite3 in dev mode. 
```sh
rails db:create
```

install active admin
```shell
rails g active_admin:install --skip-users
```

Client model

```shell
rails g model Client name:string phone_number:string email:string birthday:date
```

client resource in active admin

```shell
rails g active_admin:resource Client
```

generate webpacker
```shell
rails g active_admin:webpacker
```
