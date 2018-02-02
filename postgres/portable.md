# Portable PostgreSQL

## Installation

Download the portable zip file, extract to folder. Let's say `D:\softs\pgsql`

## Initializing DB

`-D` where the Database Directory is getting created, `-U` default superuser to create.

```batch
> D:\softs\pgsql\bin\initdb.exe -D D:\pgdata\ -U postgres
```

## Starting server

Now `D:\pgdata\` is the initializing DB has been created.

```batch
> D:\softs\pgsql\bin\postgres -D D:\pgdata\
```

or

For default user as `postgres` add `-U`

```batch
> D:\softs\pgsql\bin\pg_ctl -U postgres -D D:\pgdata\ start
```

## Checking server connection

`-d` is the `database` name, `-h` is the `server` host where it is running, `-p` where the server port is runnig.

```batch
> D:\softs\pgsql\psql -d postgres -h localhost -p 5432
```
