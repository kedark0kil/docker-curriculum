FROM nginx

COPY static-site/wrapper.sh /

COPY html /usr/share/nginx/html

CMD ["./wrapper.sh"]
