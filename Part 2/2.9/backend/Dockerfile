FROM golang:1.16

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

RUN go build

# http://localhost:5001 changed to http://localhost
ENV REQUEST_ORIGIN="http://localhost"

CMD [ "./server" ]
