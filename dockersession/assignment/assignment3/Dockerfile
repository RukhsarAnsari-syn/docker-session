FROM alpine
RUN apk add python3
RUN mkdir /app
ADD hello.py /app/hello.py
ENV MESSAGE Welcome
WORKDIR /app
RUN chmod 777 hello.py
CMD python3 hello.py
