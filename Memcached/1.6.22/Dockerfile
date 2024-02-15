FROM alpine:3.19.1
RUN apk add --no-cache memcached=1.6.22-r0
COPY ./memcached_args.txt /memcached_args.txt
COPY ./entry.sh /entry.sh
RUN chmod +x entry.sh
ENTRYPOINT [ "/entry.sh" ]