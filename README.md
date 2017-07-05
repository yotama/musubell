# Musubell

## セットアップ

- Javaのインストール
- npmのインストール

### npmパッケージのインストール

```
npm install -g yo
npm install -g generator-jhipster
npm install -g yarn
npm install -g @angular/cli
```

## 開発

### 起動

```
./gradlew
```

http://localhost:8080/

フロントのみ

```
npm start
```

### angular-cli

コンポーネント追加

```
ng generate component my-component
```

生成されるコード

```
create src/main/webapp/app/my-component/my-component.component.html
create src/main/webapp/app/my-component/my-component.component.ts
update src/main/webapp/app/app.module.ts
```

## テスト

テスト実行

```
./gradlew test
```

### クライアントのテスト

```
yarn test
```


## Docker

MySQL起動

```
docker-compose -f src/main/docker/mysql.yml up -d
```

MySQL停止

```
docker-compose -f src/main/docker/mysql.yml down
```
