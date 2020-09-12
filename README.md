# docker-jenkins-sonar
使用 Docker Compose 一键搭建基于 Jenkins & SonarQube 的 DevOps 和持续检测环境

## 使用方法

1. `docker-compose up -d` 启动容器 

2. 在 Jenkins 中配置 SonarQube Scanner，路径为 `/usr/local/sonar-scanner`