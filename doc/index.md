```bash
# コンポーネント作成

# src/app 直下に ディレクトリが作成される
# app.module.tsにも追記される
ng generate component heroes
```

```bash
# サービス作成

# src/app 直下に ファイルが作成される
ng generate service hero

ng generate service InMemoryData
```

```bash
# モジュール (ルーティング)

-- flat 
app-routingを作らない

--module=app
importに自動追加
ng generate module app-routing --flat --module=app
```


