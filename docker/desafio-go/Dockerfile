FROM golang:1.19

WORKDIR /usr/src/app

COPY fullcycle-rocks.go ./
COPY run.sh ./

RUN chmod +x run.sh

ENTRYPOINT [ "./run.sh" ]

CMD ["fullcycle-rocks.go"]
