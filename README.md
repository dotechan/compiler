# 概要
『低レイヤを知りたい人のためのCコンパイラ作成入門』の写経

# 環境
- MacOS Big Sur(11.5.1)
- プロセッサ 2.3GHz クアッドコアIntel Core i7
- Docker Desktop for Mac(3.3.1)

# 環境構築
[付録3：Dockerを使った開発環境の作成](https://www.sigbus.info/compilerbook#docker)を参考にUbuntuの仮想環境を用意する。

# コマンド
- テスト
```
$ docker run --rm -v $HOME/9cc:/9cc -w /9cc compilerbook make test
```

- コンテナ内でシェルを起動してインタラクティブに使いたい場合
```
$ docker run --rm -it -v $HOME/9cc:/9cc compilerbook 
```

# 参考文献
Rui Ueyama, 「低レイヤを知りたい人のためのCコンパイラ作成入門」, 2020-03-16, <https://www.sigbus.info/compilerbook>, （2021-08-12閲覧）.
