# version: 0.1

FROM tomcat
MAINTAINER Zhang Zh. <zhchuan7@gmail.com>

ENV LANG C.UTF-8
ENV JAVA_HOME /usr/lib/jvm/java-7-openjdk-amd64

RUN apt-get update && apt-get install -y --no-install-recommends \
    openjdk-7-jdk \
    maven \
	&& rm -rf /var/lib/apt/lists/*
