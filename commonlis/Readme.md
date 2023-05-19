

```sh
git clone https://github.com/kawadasatoshi/cl.git
cd cl
docker-compose build
docker-compose run --rm lisp_sh bash
```

作成したコンテナの中で次のコマンドを打つ

```sh
(load "hoge.lisp")
```


