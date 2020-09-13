FROM jenkins/jenkins:lts

LABEL maintainer="XUQING"

# 复制 Jenkins 的 Sonar Scanner 插件及其依赖
COPY --chown=jenkins:jenkins ./jenkins-plugins /var/jenkins_home/plugins

# 复制 Sonar Scanner 
# version:4.4.0.2170
COPY ./sonar-scanner /usr/local/sonar-scanner

EXPOSE 8080 50000