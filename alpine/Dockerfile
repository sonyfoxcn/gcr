FROM alpine:3.13
RUN set -ex && \
    apk update && \
    apk add --no-cache tzdata bash curl jq && \
    cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime && \
    rm -rf /var/cache/apk/*
