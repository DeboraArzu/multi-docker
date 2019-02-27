# Multi-docker

This is a proyect with multi containers. It is a web app that calculates the fibonacci serie it uses React as FrontEnd and in the BackEnd it has Redis, Postgress and Express.

# Travis CI
It also was build with a .travis.ci file so when I push my code to Git it automatically goes to my Travis CI account and I can keep and easy track of the tests on my proyect.
For the credentials of Docker Hub and AWS it is necessary to configure them in the environment variables of Travis CI.

# Run the project 
To run the project it is necesary to download it and be on the main project directory where is the docker-compose.yml and from the command line run docker-compose up

# Integration with ElasticBeanStalk
In the .travis.yml file on the bottom there is a deploy section so Travis can automatically push the code and ElasticBeanStalk can deploy the containers.
