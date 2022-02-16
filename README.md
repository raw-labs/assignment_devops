# RAW Labs DevOps Assignment
![RAW Cube](https://raw-labs.com/wp-content/themes/raw-labs/img/cube.svg)

## Introduction
This repository holds the RAW Labs DevOps assignment. In this project you will find a folder that holds a microservice, supplied with a Dockerfile.

### Simple RAW service
Simple RAW service is well... a simple stateless service that serves a simple HTTP message. You can deploy as many replicas of this service as you like.

This service is a NodeJS app. As such, it manages its dependencies in a package.json file, `npm install` installs the dependencies in a folder called `node_modules`. Unit tests can be executed by running `npm test`.

## The assignment
The requirement is to perform the necessary provisioning for deploying and operating this app in a Cloud provider of your choice. This can be a free tier AWS, GCP, DigitalOcean, etc. After deploying the app, you need to setup a monitoring and alerting system. The former should visualize aspects related to hardware (CPU utilization, memory usage, disk space & I/O, etc.) and software (number of successful/failed/total invocations, mean response time, etc.). Alerting should be engaged in case the number of failed invocations exceeds a given percentage of the number of total invocations and should send a notification to an email address. 

Additional notes: 
- Infrastructure-as-Code paradigm should be adopted for all aspects of this assignment  
- The selection for container orchestration is yours (Kubernetes, compose, etc.) 
- The selection for monitoring and alerting technology is also yours (Grafana, Prometheus, Splunk, Datadog, etc.) 
- If you find it difficult to get free usage for a Cloud provider, please contact us 

Upon successful execution, you will present your process, technical decisions and outcome to us. 

## Questions
If you have any questions about the assignment, feel free to contact us at <a href='mailto:pavlos@raw-labs.com'>pavlos@raw-labs.com</a> and <a href='mailto:yann@raw-labs.com'>yann@raw-labs.com</a> (basically you're strongly encouraged to do so).

Good luck!
