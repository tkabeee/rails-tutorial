### Railsアプリ生成

```bash
# ここはスルーしてOK
docker-compose run --rm web rails new . --force --database=mysql --skip-bundle
```

### プロジェクト構築

```bash
docker-compose build
```

### データベースマイグレート

```bash
docker-compose run --rm web rails db:migrate
```

### アプリケーション起動

```bash
docker-compose up
```

### bundle install

```bash
docker-compose run --rm web rails bundle install
```

### アプリケーション停止

```
docker-compose down
```