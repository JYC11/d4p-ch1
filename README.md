# Django For Professionals: Introductions

I get introduced to Docker in this chapter. I'll try to explain Docker as how I understand it. I've had some very light exposure to Docker and Docker Compose before when working with node.js so I have some idea of it.

## Docker
Image => A snapshot of the configurations of the current project(the code, the version of the programming language, the packages/libraries used, the database configs, environment variable). It is a set of instructions read from top to bottom.

Building an Image => When Docker takes the Image and sets up the environment as specified in the Image instructions(downloading programming languages, downloading packages/libraries, setting environment variables, connecting to databases).

## Docker Compose
A way to have multiple docker images and builds at once(?) separated by containers/services from what I understand.

Each service can be configured to your liking. With this we set our port, what command to use to run, where to look for in terms of Dockerfile and code.
