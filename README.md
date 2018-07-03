Overview
---
Skeleton of a Spring Boot App deployed with Jenkins and Ansible

Modules
---
* backend

  contains a runnable Spring Boot web application including `frontend` as runtime dependency. `backend` and `frontend` applications communicate via HTTP Rest. 
* frontend

  a ReactJS frontend application which sits on top of `backend`
* deployment

  the `ansible` deployment scripts
* Jenkinsfile
  
  description of the CI/CD pipeline
  