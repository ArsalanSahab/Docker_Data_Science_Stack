FROM python:3.6

MAINTAINER Muhammad Arsalan <arsalan.sahab@gmail.com>

WORKDIR /usr/src/app


RUN pip3 install --no-cache-dir --proxy=${http_proxy}\
  numpy===1.14.3 

RUN pip3 install --no-cache-dir --proxy=${http_proxy}\
  apistar==0.5.41 \
  gunicorn==19.8.1 \
  dill===0.2.7.1 \
  minio===4.0.0 \
  psycopg2-binary===2.7.4 \
  scipy \
  scikit-learn

RUN pip install --no-cache-dir --no-deps --proxy=${http_proxy}\
  pandas


EXPOSE 8000
