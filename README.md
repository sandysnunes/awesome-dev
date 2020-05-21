# awesome-dev

## Tools

1.

### JSON

1.
2.


## Docker images



## Redis
- `docker run --name redis-local -p 6379:6379 -d redis`
- `sudo apt install redis-tools #redis-cli`


## Mongo

- `docker run --name mongo-local -v /opt/mongo:/data/db -p 27017:27017 -p 28017:28017 -e MONGO_INITDB_ROOT_USERNAME=username -e MONGO_INITDB_ROOT_PASSWORD=password  -d mongo`

## Postgres

- `docker run --name pg-local -p 5432:5432 -v /opt/db-backup:/opt/db-backup -v /opt/local-db-data:/var/lib/postgresql/data -e POSTGRES_PASSWORD=postgres -d postgres:12.2`

## FTP

- `docker run -d -v /opt/ftp-local:/home/vsftpd -p 20:20 -p 21:21 -p 47400-47470:47400-47470 -e FTP_USER=user -e FTP_PASS=password -e PASV_ADDRESS=172.17.0.1 --name ftp  bogem/ftp`
