FROM python:2.7.14
MAINTAINER neo
COPY ./pip.conf /root/.pip/pip.conf
RUN pip install --upgrade pip && pip install flask flask_migrate flask_script flask_restful flask_login numpy pandas flasgger uwsgi