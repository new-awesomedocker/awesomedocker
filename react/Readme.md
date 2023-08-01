
### まずはbuild

```sh
docker-compose build
```


### 次に、シェルを起動

```sh
docker-compose run --rm react-app sh 
```

インストール用スクリプト（初回のみ起動）

```sh
npm install -g create-react-app
create-react-app react-sample
```

終わったら`exit`

### 起動用

以下のコマンドで起動

```sh
docker-compose up
```
