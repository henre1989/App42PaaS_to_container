FROM maven:3-openjdk-11
RUN apt update && apt install git -y
WORKDIR /home
RUN git clone https://github.com/shephertz/App42PaaS-Java-MySQL-Sample.git
RUN mkdir /App42PaaS-Java-MySQL-Sample/ROOT
RUN mvn package -f /home/App42PaaS-Java-MySQL-Sample/pom.xml
COPY Config.properties /App42PaaS-Java-MySQL-Sample/target/App42PaaS-Java-MySQL-Sample-0.0.1-SNAPSHOT/ROOT