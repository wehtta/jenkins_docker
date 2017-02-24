FROM daocloud.io/library/jenkins:latest
MAINTAINER Xiaoxian

USER root
RUN mkdir -p /var/log/jenkins
RUN chown -R jenkins:jenkins /var/log/jenkins

#jenkins plugins, settings will be into /var/jenkins_home

USER jenkins
