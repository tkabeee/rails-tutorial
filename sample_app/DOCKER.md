### Railsアプリ生成

```bash
docker-compose run --rm web rails new .
```

### プロジェクト構築

```bash
docker-compose build
```

### データベースマイグレート

```bash
docker-compose run --rm web rails db:migrate
```

### bundle install

```bash
docker-compose run --rm web rails bundle install
```

### アプリケーション起動・停止

```
docker-compose up
docker-compose down

docker-compose start
docker-compose stop
```