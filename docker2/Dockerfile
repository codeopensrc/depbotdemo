FROM bitnami/prometheus-operator:0.69.1-debian-11-r0
LABEL org.opencontainers.image.source="https://github.com/codeopensrc/depbotdemo"
RUN apk update && \
    apk upgrade && \
    apk add curl bash
RUN pip3 install flask flask-httpauth
