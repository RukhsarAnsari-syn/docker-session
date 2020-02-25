FROM alpine
RUN mkdir /app
ADD test1.sh /app/test1.sh
ENV LOOP_CNT 5
ENV MESSAGE Welcome
WORKDIR /app
RUN chmod 777 test1.sh
CMD ["/bin/sh","test1.sh"]
