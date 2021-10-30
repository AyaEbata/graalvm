# GraalVMおためし

以下でGraalVMのコマンド打てるよ✌️

```
$ docker-compose run graalvm bash
```

## Javaで実行
```
$ java --version   # バージョン確認
$ javac Main.java  # コンパイル
$ java Main        # 実行
```

## Node.jsで実行
```
$ gu install nodejs           # nodeのインストール
$ $JAVA_HOME/bin/node -v      # バージョン確認
$ $JAVA_HOME/bin/node app.js  # 実行
```

## Native Imageで実行
```
$ gu install native-image  # NativeImageのインストール
$ javac Main.java          # コンパイル
$ native-image Main        # NativeImageのビルド
$ ./main                   # 実行
```
