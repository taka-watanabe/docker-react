# docker-react
reactテスト用

Dockerイメージのビルド
```
docker-compose build
```

create-react-appとReactのインストール
```
docker-compose run --rm node sh -c “npm install -g create-react-app && create-react-app react-sample"
```

実行
```
docker-compose up
```