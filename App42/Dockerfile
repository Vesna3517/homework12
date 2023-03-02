FROM maven:3.2-jdk-8
RUN apt update && apt install wget unzip -y --force-yes
RUN wget https://github.com/shephertz/App42PaaS-Java-MySQL-Sample/archive/master.zip
RUN unzip master.zip
WORKDIR /usr/src/App42PaaS/master
CMD ["mvn", "package"]