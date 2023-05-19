

## how to run common lisp

common lisp container is easy.

just run below command.

```sh
git clone https://github.com/awsomedocker/commonlisp.git
cd awsomedocker/commonlisp
docker-compose build
docker-compose run --rm lisp_sh sbcl
```

and run lisp script in the container.


```sh
(load "hoge.lisp")
```

Done.




