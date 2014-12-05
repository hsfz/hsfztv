FROM dockerfile/nginx

ADD nginx.conf /etc/nginx/nginx.conf

CMD mkdir -p /data/log/nginx && \
    nginx

VOLUME ["/data"]
EXPOSE 80

