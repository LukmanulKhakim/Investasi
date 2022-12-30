### Investasi API

Clone Repo
```
git clone https://github.com/LukmanulKhakim/Investasi
```
create .env file
```
DB_USER = root
DB_PWD = your password
DB_HOST = localhost
DB_PORT = 3306
DB_NAME = create database name
```

Run Local
```
go run sever.go
```

Routing

```
POST /info
POST /invest
GET  /invest
PUT /invest/:id

```