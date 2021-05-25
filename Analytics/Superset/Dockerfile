FROM apache/superset

USER root

RUN pip install mysqlclient
RUN pip install pinotdb
RUN pip install pydruid
RUN pip install sqlalchemy-clickhouse
RUN pip install psycopg2

USER superset