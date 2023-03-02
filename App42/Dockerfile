FROM maven:3.2-jdk-8
RUN apt update
RUN apt install git -y
RUN git clone https://github.com/shephertz/App42PaaS-Java-MySQL-Sample.git /usr/src/App42PaaS
WORKDIR /usr/src/App42PaaS/
CMD ["mvn", "package"]