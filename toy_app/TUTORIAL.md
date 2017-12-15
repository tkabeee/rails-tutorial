```bash
docker-compose run --rm web rails generate scaffold Micropost content:text user_id:integer
docker-compose run --rm web rails db:migrate
```

```bash
docker-compose run --rm web rails console
```