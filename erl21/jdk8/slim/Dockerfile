FROM erlang:21-slim
ENV LANG C.UTF-8
ENV LC_ALL C.UTF-8
RUN apt-get update\
  && apt-get install openjdk-8-jdk-headless git openssh-client -y\
  && apt-get clean
