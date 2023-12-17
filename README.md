# Docker Compose Scripts

This repository contains predefined [Docker Compose](https://docs.docker.com/compose/) collection scripts which allows you to deploy Docker containers fast and easy.

## Docker Compose List
|Docker Compose File |Description  | Default Entry Points|
--- | --- | ---|
|[Gitea](/gitea/docker-compose.yml)|A painless self-hosted Git service. The fork of Gogs.|http://127.0.0.1:3000 or ssh://127.0.0.1:22|
|[Gogs](/gitea/docker-compose.yml)|A painless self-hosted Git service.|http://127.0.0.1:3000 or ssh://127.0.0.1:22|
|[Microsoft SQL Server](/mssql/docker-compose.yml)|Relational model database server produced by Microsoft. _**Note: This image is proprietary software. Use it for development purposes only otherwise purchase the license on official Microsoft Store.**_ |localhost:1433|
|[Microsoft SQL Server for Apple Silicon](/mssql/docker-compose.yml)|Relational model database server produced by Microsoft and supports to deploy on Apple Silicon chips (e.g. M1). _**Note: This image is proprietary software. Use it for development purposes only otherwise purchase the license on official Microsoft Store.**_ |localhost:1433|
|[Postgres SQL Server](/pgsql/docker-compose.yml) |Powerful, open source object-relational database system. | localhost:5432 for Server and http://localhost:5050 for PGAdmin4|
|[OpenSSL Webterm](/openssl-webterm/docker-compose.yml) |User-friendly web app to use OpenSSL, based on WebAssembly. | http://localhost:4300|
|[qBittorrent](/qbittorrent/docker-compose.yml) |The qBittorrent project aims to provide an open-source software alternative to µTorrent.  | http://localhost:8585|
|[MariaDB](/maria-db/docker-compose.yml) |Fork of the one of the most popular open source relational databases.  | http://localhost:40000 for Server and http://localhost:40001 for phpMyAdmin|

## License

[The MIT License](/LICENSE)