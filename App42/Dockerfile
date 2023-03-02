FROM maven:3.5.0-jdk-8
RUN apt update && apt install git -y
RUN git clone https://github.com/shephertz/App42PaaS-Java-MySQL-Sample.git /usr/src/App42PaaS/
WORKDIR /usr/src/App42PaaS/
CMD ["mvn", "package"]