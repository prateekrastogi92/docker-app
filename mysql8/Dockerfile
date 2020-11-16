FROM percona:8.0

USER root

ADD my.cnf /etc/mysql/conf.d/my.cnf

RUN chmod 664 /etc/mysql/conf.d/my.cnf

USER mysql
EXPOSE 3306
CMD ["mysqld"]
