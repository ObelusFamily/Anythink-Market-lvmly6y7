# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Install Docker

First step to getting started with your development environment is to get Docker for your system. You can find installation files on https://docs.docker.com/get-docker/

You can check if Docker has installed correctly by opening your terminal and running the following commands:
`docker -v` and `docker-compose -v`

### Installing Anythink project


1. Clone the Github repository for your Anythink account on your local machine 
2. Open terminal to the **root directory** of the project
3. Run `docker-compose up` from the **root directory**
4. Docker will load up Anythink's frontend and backend. This may take a few minutes
5. Once setup is done, we can check if Docker backend is working correctly by **pointing your browser** to http://localhost:3000/api/ping and get a response
6. To check the frontend, open the browser to http://localhost:3001/register
7. Create a new user for Anythink
8. Congratuations! You've successfully setup 😊

### Commands Used

1. `docker-compose up` - Run scripts on one of the containers. Run this command when the terminal is pointing to the directory we want to execute.
2. `docker exec` - Run commands on a running container
