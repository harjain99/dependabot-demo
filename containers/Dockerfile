FROM 242040583208.dkr.ecr.us-east-2.amazonaws.com/brightspot-cloud/tomcat:9.0.65.344-jdk11-temurin

ARG WAR_ARTIFACT
COPY $WAR_ARTIFACT /usr/local/tomcat/webapps/ROOT.war

# 9.0.65.344 works maybe
