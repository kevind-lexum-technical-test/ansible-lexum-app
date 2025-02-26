# ansible-lexum-app

This ansible code serve to setup a java app in docker. It will be run by a server to:
- Install docker
- Get value to SSM and put as env variable for docker
- Login to ecr to retrieve run the docker image
- Run the docker container and push logs into cloudwatch