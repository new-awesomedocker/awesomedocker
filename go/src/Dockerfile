# image取得(容量が小さいalpineを選択)
FROM golang:1.17.6-alpine

# ワーキングディレクトリの設定
WORKDIR /go/src/
RUN apk add git
CMD godoc -http 0.0.0.0:6060
