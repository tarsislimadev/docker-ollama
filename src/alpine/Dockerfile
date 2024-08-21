FROM ubuntu:jammy

RUN apk update

RUN apk add --no-cache nano curl lshw curl lshw bash

RUN curl -fsSL https://ollama.com/install.sh | sh

CMD ollama
