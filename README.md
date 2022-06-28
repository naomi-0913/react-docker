## 環境構築

1. git clone
```
git clone https://github.com/naomi-0913/react-docker.git
```

2. 該当ディレクトリに移動

3. （Dockerが起動していることを確認の上実行）　
```
docker-compose build
```

4. モジュールインストール
```
docker-compose run --rm react_node_service sh -c “cd react-sample && nom install”
```

5. コンテナ起動
```
docker-compose up -d
```

6. 以下にアクセスして画面表示されれば、OK！
```
http://localhost:3000/
```
