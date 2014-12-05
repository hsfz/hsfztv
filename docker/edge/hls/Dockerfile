FROM ziyan/srs

ADD hls.conf /etc/hls.conf

CMD mkdir -p /data/root/live && \
    mkdir -p /data/log/hls && \
    srs -c /etc/hls.conf

VOLUME ["/data"]
EXPOSE 1935

