FROM alpine:3.20

RUN apk update

RUN apk add --no-cache nano curl lshw curl lshw bash

RUN curl -fsSL https://ollama.com/install.sh | sh

CMD ollama
