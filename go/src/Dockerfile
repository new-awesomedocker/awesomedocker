# image取得(容量が小さいalpineを選択)
FROM golang:1.17.6-alpine


# ワーキングディレクトリの設定
WORKDIR /go/src/
RUN go get golang.org/x/tools/cmd/godoc
ENV GOROOT=/go/
RUN apk add git
RUN git clone https://github.com/minegishirei/explainable_moby.git
CMD godoc -http 0.0.0.0:6060
