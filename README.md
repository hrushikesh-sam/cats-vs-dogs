# Cats vs Dogs
cats vs dogs is an application which i used to understand fundamental principles of some technology stacks.

## The stacks used in this project are    
    * docker
    * docker-compose
    * Flask
    * Redis
    * dot net (.NET)
    * Postgres
    * Express js

## to try the application that I've built

### step 1
you need to install docker on your local system
follow the link if you dont have it already
[install docker](https://docs.docker.com/compose/install/)


### step 2
download docker-compose for running the yaml file
follow  the link if you dont have it aleady
[install docker-compose](https://docker-docs.netlify.app/compose/install/)
for ubuntu 20.04 lts
    
    sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose)
    
give executable permissions
    
    sudo chmod +x /usr/local/bin/docker-compose'''
check version
 
    docker-compose --version
### step 3
install the docker-compose file from the repository by cloning into local repository



### step 4
run the docker-compose.yml file by running this command in terminal as superuser
 
    docker-compose up

### step 5
check the application running on ports 5000 for voting app and 5001 for answer app
