FROM python:3.9.9-alpine
LABEL org.opencontainers.image.source="https://github.com/docker-library/python"
RUN apk update && \
    apk upgrade && \
    apk add curl bash
RUN pip3 install flask flask-httpauth
