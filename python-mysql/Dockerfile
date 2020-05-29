FROM python:2.7-alpine
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN echo 'Asia/Shanghai' >/etc/timezone

ENV LANG=C.UTF-8

VOLUME /code
WORKDIR /code


RUN pip install pymysql
RUN pip install pika

CMD ["python2","app.py"]
