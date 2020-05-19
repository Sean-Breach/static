# Static Website for Jenkins Automation on AWS

## Project Summary
This is a Udacity Project for the [Cloud DevOps Engineer Nanodegree](https://www.udacity.com/course/cloud-dev-ops-nanodegree--nd9991). In this project we build a Jenkins Pipeline on AWS.

## Setting Up Environment

1) Clone / Download Repo to your [Git Hub](https://github.com) and local environment `git clone git@github.com:Sean-Breach/static.git`
2) Setup your [Jenkins Environment](https://aws.amazon.com/getting-started/hands-on/setup-jenkins-build-server/)
  * Install the [Blue Ocean](https://www.jenkins.io/projects/blueocean/) Plugin
  * Install [Tidy](https://www.html-tidy.org/) on Linux Server 
  * Link Your Git Hub Account to Jenkins And Build Away!
  
## Repo File Documentation

* **JenkinsFile** - Jenkins Pipeline that will
  * Using [Tidy](https://www.html-tidy.org/), Lint index.html
  * If Lint Successful, Upload index.html to AWS S3 Bucket
* **LICENSE** - License file for the Project
* **README.md** - Your Helpful Guide to this Crazy Project's Purpose
* **index.html** - Simple Static Webpage
