FROM alpine:3.15

COPY usr/local/hello/ /usr/local/hello
RUN chmod 777 /usr/local/hello/hello.sh 

ENTRYPOINT ["/usr/local/hello/hello.sh"]
