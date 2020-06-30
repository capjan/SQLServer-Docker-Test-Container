# SQL-Server Test Server (via Docker)

This repository contains a test environment for SQL-Server via Docker.

## Requirements

* Up and running Docker Host and installed docker-compose orchestration.
* Do NOT use this container in production environments without further configuration.

## Info

* SQL-Server 2019

* Connection String

  ```
  Server=localhost;Database=master;User=sa;Password=Your_password123;
  ```

* Stores the database data in a local folder: **sqlserver-data**

* Check docker-compose.yml for further information.

* [SQL-Server image documentation on Docker Hub](https://hub.docker.com/_/microsoft-mssql-serverl)