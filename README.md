# Lumen + MySQL + Docker

Part I:

[Setting Up Lumen and MySQL With Docker - Part I](https://yossiabramov.com/blog/setting-up-lumen-and-mysql-with-docker-part-i)

Part II:

[Setting Up Lumen and MySQL With Docker - Part II](https://yossiabramov.com/blog/setting-up-lumen-and-mysql-with-docker-part-ii)

1. Rename `.env.example` to `.env` (or use your own `.env`)

2. In `.env`, change `DB_HOST=127.0.0.1` to `DB_HOST=your_mysql_container_name` (`DB_HOST=db` in this example)

3. Build and run project with:

```
docker-compose --env-file .env up --build
```
