FROM    tiangolo/uwsgi-nginx-flask:python2.7

RUN     apt-get update && \
        apt-get install libmysqlclient-dev -y && \
        pip install flask-mysql
 
ADD     /azure-vote /app