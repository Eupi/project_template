FROM alpine:3.7
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip && \
    apk --purge -v del py-pip
CMD tail -f /dev/null
