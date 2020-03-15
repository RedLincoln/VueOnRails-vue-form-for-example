# Vue on Rails Example using vue-form-for package form vueonrails repository

## Notas

El proyecto esta configurado para utilizar una base de datos [PostgreSQL](https://www.postgresql.org/) si es necesario cambiar los datos de configuración solo es necesario cambiar los campos de `host, username o password` en el fichero `ROOT_RAILS/config/database.yml` los datos que ya tienen son:

```
host: localhost
username: postgres
password: password
```


## Intalación

```
git clone https://github.com/RedLincoln/VueOnRails-vue-form-for-example
cd VueOnRails-vue-form-for-example
bundle install
npm install
```

## Arrancando el servidor

```
rails db:create
rails db:migrate
rails server
```