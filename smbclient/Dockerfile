ARG ALPINE_VERSION=3
FROM alpine:$ALPINE_VERSION

ARG SAMBA_CLIENT_VERSION
RUN apk add --no-cache samba-client=$SAMBA_CLIENT_VERSION && mkdir /data
WORKDIR /data

ENTRYPOINT [ "smbclient" ]
