FROM jupyter/pyspark-notebook

USER root

RUN apt-get update
RUN apt-get install default-jdk -y

RUN pip install --proxy=${http_proxy}\
    psycopg2-binary\
    minio

USER jovyan
