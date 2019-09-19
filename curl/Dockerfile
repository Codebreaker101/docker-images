ARG ALPINE_VERSION=3
FROM alpine:$ALPINE_VERSION

ARG CURL_VERSION
RUN apk add --no-cache curl=$CURL_VERSION && mkdir /data
WORKDIR /data

ENTRYPOINT [ "curl" ]
