FROM jenkins/jenkins:lts-jdk11

COPY plugins.txt /usr/share/jenkins/ref/plugins.txt
RUN jenkins-plugin-cli --plugin-file /usr/share/jenkins/ref/plugins.txt

COPY seedJob.xml /usr/share/jenkins/ref/jobs/seed-job/config.xml

ENV JAVA_OPTS -Djenkins.install.runSetupWizard=false
USER root
RUN apt-get update && apt-get install -y maven
ENV MAVEN_HOME /usr/share/maven
#ENV JAVA_HOME /opt/java/openjdk