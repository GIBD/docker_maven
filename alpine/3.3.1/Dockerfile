FROM gibdfrcu/base:alpine_jdk1.8.112_py2.7.12

MAINTAINER Ramiro Rivera <ramarivera@gmail.com>

ENV MAVEN_VERSION="3.3.1" 

ENV	M2_HOME="/opt/apache-maven-${MAVEN_VERSION}" 
ENV MAVEN_OPTS="-Xms256m -Xmx512m"
ENV M2="${M2_HOME}/bin"
ENV PATH="${M2}:${PATH}"

RUN wget -q -O - http://mirrors.dcarsat.com.ar/apache/maven/maven-3/${MAVEN_VERSION}/binaries/apache-maven-${MAVEN_VERSION}-bin.tar.gz | tar -xzf - -C /opt 