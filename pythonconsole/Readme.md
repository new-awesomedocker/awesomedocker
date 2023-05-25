
```sh
git clone https://github.com/new-awesomedocker/awesomedocker.git
cd awesomedocker/pythonconsole/
docker image build -t pythonconsole .
docker run -it -v ./code:/code pythonconsole bash
```



## commands:コマンド入力



1. clone this repo

本リポジトリのソースコードをダウンロードします。

```sh
git clone https://github.com/new-awesomedocker/awesomedocker.git
```


2. move to "pythonconsole" directory

pythonconsoleディレクトリにcdコマンドで移動します。

```sh
cd new-awesomedocker/pythonconsole/
```


3. build pythonconsole image

pythonconsoleイメージをbuildします。

```sh
docker image build -t pythonconsole .
```


4. run pythonconsole container

先ほど作成した、pythonconsoleイメージコンテナをrunします。

```sh
docker run -it -v ./code:/code pythonconsole bash
```






