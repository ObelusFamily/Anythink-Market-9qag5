# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Download and install Docker, https://www.docker.com/get-started/
- Go from the root of the project, run `docker-compose up`
- After the Docker image is running, verify the services are running
  - Verify the backend is running at http://localhost:3000/api/ping
  - Verify that the front end is running at http://localhost:3001/
  - Create a user at http://localhost:3001/ and verify that the account is created.
