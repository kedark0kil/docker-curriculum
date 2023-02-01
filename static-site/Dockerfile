FROM kedark0kil/task-fluxcd:1.0

WORKDIR static-site/
COPY html/* /usr/share/nginx/html/

COPY static-site/wrapper.sh /

CMD ["./wrapper.sh"]