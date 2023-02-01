FROM nginx

COPY static-site/html/* /usr/share/nginx/html/

COPY static-site/wrapper.sh /

CMD ["./wrapper.sh"]
