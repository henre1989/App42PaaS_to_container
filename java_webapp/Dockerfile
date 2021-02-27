FROM maven:3-openjdk-11
RUN apt update && apt install git -y
WORKDIR /home
RUN git clone https://github.com/shephertz/App42PaaS-Java-MySQL-Sample.git
COPY Config.properties /App42PaaS-Java-MySQL-Sample/WebContent
RUN mvn package -f /home/App42PaaS-Java-MySQL-Sample/pom.xml