## Dockerの起動から停止まで

### 起動
```
// dockerのビルド
docker-compose build

// dockerの起動
docker-compose up -d

// 確認
docker-compose ps

```

### 実行
```
// bash 起動
docker-compose exec java bash

// コンパイル
root@5b7be900c329:/usr/src# javac Main.java

// 実行
root@5b7be900c329:/usr/src# java Main
Hello World!

// bash 終了
root@5b7be900c329:/usr/src# exit

```

### クリーンアップ
```
// docker終了
docker-compose down

// imageの確認
docker image ls
REPOSITORY        TAG       IMAGE ID       CREATED       SIZE
java-learn_java   latest    a9a75dbc79b0   9 hours ago   439MB

// imageの削除
docker image rm　java-learn_java 
```