# README

## SetUp

### 1. コンテナビルド

```bash
$ cd sk-agent-client-manager-app
$ docker compose build
```

### 2. コンテナ立ち上げる

```bash
$ cd sk-agent-client-manager-app
$ docker compose up
```

### 3. Database 作成

```bash
$ docker compose exec web bash
root@xxxxxxx:/myapp# rails db:create
root@xxxxxxx:/myapp# exit
```

### 4. サイト参照

http://localhost:3000/

TOP ページが参照できれば問題なし