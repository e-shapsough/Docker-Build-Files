FROM alpine:3.19.1
RUN apk add --no-cache redis=7.2.4-r0
COPY ./redis.conf /etc/redis.conf
ENTRYPOINT [ "/usr/bin/redis-server", "/etc/redis.conf" ]