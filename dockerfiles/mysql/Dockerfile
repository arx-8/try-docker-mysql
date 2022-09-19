FROM mysql:8.0.30

EXPOSE 3306

ADD ./my.cnf /etc/mysql/conf.d/my.cnf

USER mysql
CMD ["mysqld"]
