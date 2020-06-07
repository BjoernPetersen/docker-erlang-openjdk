FROM erlang:23
ENV LANG C.UTF-8
ENV LC_ALL C.UTF-8
RUN apt-get update\
  && apt-get install openjdk-8-jdk git openssh-client -y\
  && apt-get clean
