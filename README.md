# Simple DevOps problem
A simple static file web problem to be used as a DevOps test.

## The problem
Build a pipeline to automatically deploy and host a static website page on the internet. The application has to be containerized using something like a Dockerfile or any other OCI standard approach.

## The application to be deployed
The application you will be deploying is a static website. The files for this website can be found in `/dist/success-app.tar.gz`. Once the application is deployed, you should be able to view it in your browser. An example can be seen below.

![example mock](./success-app.jpg)

## Functional requirements / environmental limitations
* Code used during your solution should be on a public git repo.
* The application should be deployed using one of the below deployment pipeline tools as part of your git repo.
  * Gitlab CI/CD
  * Github Actions
  * Bitbucket pipelines
* The static files must be hosted inside a container using any open source web server.
* The application should be running on the public internet.
* The website should be accessible using a DNS instead of just an IP address.

## Tips
* Most cloud hosting providers will give you free credits to host your app.
* Create any cloud resources using an infrastructure as code pattern.
