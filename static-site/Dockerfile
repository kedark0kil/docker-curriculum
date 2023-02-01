FROM nginx

WORKDIR static-site/
COPY html /usr/share/nginx/html

COPY static-site/wrapper.sh /

CMD ["./wrapper.sh"]