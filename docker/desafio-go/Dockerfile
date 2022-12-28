FROM golang:1.19-alpine as mother

WORKDIR /app

COPY . .

RUN go build -o /main main.go

FROM scratch

WORKDIR /

COPY --from=mother /main /main

ENTRYPOINT [ "/main" ]
