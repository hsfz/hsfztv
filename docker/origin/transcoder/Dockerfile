FROM ziyan/srs

ADD srs.conf /etc/srs.conf

CMD mkdir -p /data/root/live && mkdir -p /data/log/ffmpeg && srs -c /etc/srs.conf

VOLUME ["/data"]
EXPOSE 1935

