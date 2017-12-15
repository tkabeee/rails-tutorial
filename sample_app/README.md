Gemsインストール

```bash
docker-compose run --rm web bundle install --without production
docker-compose run --rm web bundle update
```

データベースへのマイグレーション

```bash
docker-compose run --rm web rails db:migrate
```

Railsコンソール

```bash
docker-compose run --rm web rails console
```

静的ページ生成

```bash
docker-compose run --rm web rails generate controller StaticPages home help
```