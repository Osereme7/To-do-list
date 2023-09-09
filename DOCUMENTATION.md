1. Introduction
This is a todo app writted in html css and javascript to keep track of events. tick off the one you have done and delete it after

2. Getting Started
Prerequisites
To run this application you need docker and nginx installed

Installation
Clone the repository
Install docker
Install nginx
run the docker file
check the application on port 80

3. Development
Folder Structure
It is one folder with all the files

Dependencies
No dependecies are needed for this application to run but nginx

Development Environment
Can be deployed on local machine or ec2 instance

4. Dockerization
Get the nginx image and copy the files from the current directory to /usr/share/nginx/html.

5. Continuous Integration and Deployment
CI pipeline is sset up to build the docker image and push it to dockerhub.