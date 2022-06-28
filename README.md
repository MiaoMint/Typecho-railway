## Please do not upload attachments, otherwise they will be lost
## Please do not upload attachments, otherwise they will be lost
## Please do not upload attachments, otherwise they will be lost
## 请不要上传附件，否则会丢失
## 请不要上传附件，否则会丢失
## 请不要上传附件，否则会丢失

## Deploy on Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/wDoaNQ?referralCode=OzVKh7)

## Environment Variables

### `TIMEZONE`

default: `UTC`

Server timezone, eg: `Asia/Shanghai`

### `MEMORY_LIMIT`

PHP memory limit, eg: `100M`

### `MAX_POST_BODY`

eg: `50M`

### `TYPECHO_INSTALL`

default: `0`

Set to `1` if you want to run installation script automatically.

### `TYPECHO_DB_ADAPTER`

default: `Pdo_Mysql`

Database driver for typecho, could be: `Pdo_Mysql`, `Pdo_SQLite`, `Pdo_Pgsql`, `Mysqli`, `SQLite`, `Pgsql`.

### `TYPECHO_DB_HOST`

default: `localhost` 

Database server host, only available for mysql and pgsql drivers.

### `TYPECHO_DB_PORT`

default: `3306`(for mysql) or `5432`(for pgsql)

Database server port, only available for mysql and pgsql drivers.

### `TYPECHO_DB_USER`

`*` required for mysql and pgsql drivers

Database username, only available for mysql and pgsql drivers.

### `TYPECHO_DB_PASSWORD`

`*` required for mysql and pgsql drivers

Database password, only available for mysql and pgsql drivers.

### `TYPECHO_DB_FILE`

`*` required for sqlite driver

Database file storage path, only available for sqlite driver.

### `TYPECHO_DB_DATABASE`

`*` required for mysql and pgsql drivers

Database name of typecho, only available for mysql and pgsql drivers.

### `TYPECHO_DB_PREFIX`

default: `typecho_`

The prefix of all tables.

### `TYPECHO_DB_ENGINE`

default: `InnoDB`

Mysql database engine, only available for mysql driver.

### `TYPECHO_DB_CHARSET`

default: `utf8`(for pgsql) or `utf8mb4`(for mysql)

Database charset, only available for mysql and pgsql drivers.

### `TYPECHO_DB_NEXT`

default: `none`

The action to perform when there are already having some application tables in database.

* `none`: Do nothing, just exit.
* `keep`: Keep these tables, and skip the init step.
* `force`: Delete these tables, and init data again.

### `TYPECHO_SITE_URL`

`*` required

Your website url, for example: `https://your-domain.com`

### `TYPECHO_USER_NAME`

default: `typecho`

The admin username to create.

### `TYPECHO_USER_PASSWORD`

default: a random 8 characters string.

The admin password to create.

### `TYPECHO_USER_MAIL`

default: `admin@localhost.local`

The email address of admin to create.
