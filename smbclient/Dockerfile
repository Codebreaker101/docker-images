FROM alpine:3
RUN apk add --no-cache samba-client=4.10.8-r0 && mkdir /data

WORKDIR /data
ENTRYPOINT [ "smbclient" ]
#ENTRYPOINT [ "/bin/sh", "-c" ]