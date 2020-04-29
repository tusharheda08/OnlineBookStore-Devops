# use a node base image
FROM openjdk

# set maintainer
MAINTAINER Tushar Heda <tusharheda08@gmail.com>

ADD onlinebookstore-0.0.1-SNAPSHOT.war onlinebookstore-0.0.1-SNAPSHOT.war

ENTRYPOINT ["java", "-war", "onlinebookstore-0.0.1-SNAPSHOT.war"]

EXPOSE 8090