# RAW Labs DevOps Assignment
![RAW Cube](https://raw-labs.com/wp-content/themes/raw-labs/img/cube.svg)

## Introduction
This repository holds the RAW Labs DevOps assignment. In this project you will find a folder that holds a microservice, supplied with a Dockerfile.

### Simple RAW service
Simple RAW service is well... a simple stateless service that serves a simple HTTP message. You can deploy as many replicas of this service as you like.

This service is a NodeJS app. As such, it manages its dependencies in a package.json file, `npm install` installs the dependencies in a folder called `node_modules`. Unit tests can be executed by running `npm test`.

## The assignment
The requirement is to incorporate a proper CI/CD methodology. You may use GitLab with GitLab runner. You can create a free account at [https://gitlab.com/](https://gitlab.com/).

Addtional requirements include the following:
- [ ] Test should be run on the pipeline and it should not be able to proceed if it fails
- [ ] The app should be deployed to a Kubernetes cluster (take a look at Minikube)
- [ ] Multiple feature branches should be able to live alongside each other in the cluster
- [ ] Gather metrics from deployed application
- [ ] Alerting in-case of anomalies in application

Upon successful execution, you will present your process, technical decisions and outcome to us.

## Questions
If you have any questions about the assignment, feel free to contact us at <a href='mailto:pavlos@raw-labs.com'>pavlos@raw-labs.com</a> and <a href='mailto:yann@raw-labs.com'>yann@raw-labs.com</a> (basically you're strongly encouraged to do so).

Good luck!
