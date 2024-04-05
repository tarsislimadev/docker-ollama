FROM ubuntu:jammy

RUN apt update -y && apt install -y nano curl lshw

RUN curl -fsSL https://ollama.com/install.sh | sh

CMD ollama
