# Dokku Backup

Dokku Backup is a plugin for [Dokku](https://github.com/progrium/dokku) that dump on every deploys a mongodb database

## Installation

# dokku 0.4+
```
$ dokku plugin:install https://github.com/agalisteo/dokku-backup-mongodb
```

## Commands

```sh
$ dokku help
    backup:set <app> <database_name>                 Set database name
    backup:clear <app>                               Clears database name
    backup:get <app>                                 Display database name
```
