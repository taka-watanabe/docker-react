# docker-react
reactテスト用

Dockerイメージのビルド
```
docker-compose build
```

create-react-appとReactのインストール
```
docker-compose run --rm node sh -c “npx create-react-app react-sample --templete typescript"
```

実行
```
docker-compose up
```