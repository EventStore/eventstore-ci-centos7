# Description
Docker Image for build of EventStore on Centos 7 hosted at https://hub.docker.com/r/eventstore/eventstore-ci-centos7/
The build is currently used by our CI (Azure Pipelines)

### Base Image: `centos:7`  
### Installs:
- mono 5.16.0
- dotnet-sdk-2.1
- node.js 8.11.4
- fpm (latest)
- awscli (latest)