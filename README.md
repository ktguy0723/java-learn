## Dockerの起動から停止まで

```
// dockerのビルド
docker-compose build

// dockerの起動
docker-compose up -d

// 確認
docker-compose ps

```

```
// インスペクション
docker-compose exec java bash

// コンパイル
root@5b7be900c329:/usr/src# javac Main.java

// 実行
root@5b7be900c329:/usr/src# java Main
Hello World!

// 終了
root@5b7be900c329:/usr/src# exit

docker-compose down
```
