

## CDN

### nginx

```sh
git clone https://github.com/new-awesomedocker/awesomedocker.git
cd awesomedocker/nginx
docker-compose up
```

and see http://localhost



## webAPP

### React

https://docker.hatenablog.jp/entry/2023/05/18/213054


### flask


```sh
git clone https://github.com/new-awesomedocker/awesomedocker.git
cd awesomedocker/flask/
docker image build -t flask .
docker run -it -p 80:80 -v ./code:/code flask bash
```

`python main.py`


ブラウザから http://localhost/

にアクセスしてみてください。
    

### django

```sh
git clone https://github.com/new-awesomedocker/awesomedocker.git
cd awesomedocker/django/
docker image build -t django .
docker run -it -p 80:80 -v ./code:/code django bash
```

and `python mysite/manage.py runserver 0.0.0.0:80`

access to http://localhost/


## web system

### knowledge


```sh
git clone https://github.com/new-awesomedocker/awesomedocker.git
cd awesomedocker/knowledge
docker-compose up
```

access to http://localhost/:8080


## プログラミング開発環境

### commonlisp

```sh
git clone https://github.com/new-awesomedocker/awesomedocker.git
cd awesomedocker/commonlisp
docker-compose build
docker-compose run --rm lisp_sh sbcl
```

### python

```sh
git clone https://github.com/new-awesomedocker/awesomedocker.git
cd awesomedocker/pythonconsole/
docker image build -t pythonconsole .
docker run -it -v ./code:/code pythonconsole bash
```

