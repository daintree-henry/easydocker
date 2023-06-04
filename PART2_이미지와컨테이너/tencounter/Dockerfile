FROM alpine:latest

RUN apk add --no-cache bash

WORKDIR /app

COPY . /app

RUN chmod +x /app/script.sh

CMD ["/app/script.sh"]
