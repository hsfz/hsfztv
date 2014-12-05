FROM ziyan/srs

ADD distribute.conf /etc/distribute.conf

CMD mkdir -p /data/log/distribute && \
    srs -c /etc/distribute.conf

VOLUME ["/data"]
EXPOSE 1935

