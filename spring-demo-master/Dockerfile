FROM centos
RUN  yum -y install wget
COPY spring-demo-0.0.1-SNAPSHOT.jar /home/
RUN wget -P /home/ --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" https://download.oracle.com/otn-pub/java/jdk/8u201-b09/42970487e3af4f5aa5bca3f542482c60/jdk-8u201-linux-x64.rpm 
RUN rpm -ivh /home/jdk-8u201-linux-x64.rpm
EXPOSE 8080

