# ActiveMQ on OpenShift

This repository provides a Dockerfile for ActiveMQ and a template to build and deploy this image on the OpenShift Container Platform. 

Clone the repository and execute the following command in your cluster to deploy:
``` 
  oc process -f https://github.com/dedalus-enterprise-architect/activemq/master/activemq-template.yaml | oc apply -f - 
``` 
