

## commands:コマンド入力


1. clone this repo

本リポジトリのソースコードをダウンロードします。

```sh
git clone https://github.com/kawadasatoshi/PythonImages.git
```


2. move to "pythonconsole" directory

pythonconsoleディレクトリにcdコマンドで移動します。

```sh
cd PythonImages/pythonconsole/
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






