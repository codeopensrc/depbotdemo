FROM nginx/nginx-ingress:3.3.1-alpine
LABEL org.opencontainers.image.source="https://github.com/kubernetes/ingress-nginx"
RUN apk update && \
    apk upgrade && \
    apk add curl bash
RUN pip3 install flask flask-httpauth
