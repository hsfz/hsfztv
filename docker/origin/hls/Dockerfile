FROM ziyan/srs

ADD srs.conf /etc/srs.conf

CMD mkdir -p /data/log && srs -c /etc/srs.conf

VOLUME ["/data"]
EXPOSE 1935

