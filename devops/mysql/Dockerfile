# load mysql
FROM mysql:5.7

# install locale
RUN apt-get update --yes
RUN apt-get install locales --yes
RUN apt-get install vim --yes

ADD ./devops/mysql/mysqld.cnf /etc/mysql/mysql.conf.d/mysqld.cnf