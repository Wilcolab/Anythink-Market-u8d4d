# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker from the following link: https://docs.docker.com/get-docker/
2. Verify that the installation was successful by running docker -v and docker-compose -v in your terminal.
3. Run docker-compose up in the project root directory to start the project.
4. Verify that the backend is up and running by accessing http://localhost:3000/api/ping
5. Verify that the frontend is running and connected to the backend by accessing http://localhost:3001/register
6. Create a user on the newly accessed page.
