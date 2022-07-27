# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Install [Docker](https://docker.com)
1. Verify that Docker is installed correctly by running:
  1. `docker -v` and
  1. `docker-compose -v`
1. Navigate to your project directory in a terminal: `cd <project directory>`
1. In that same terminal, start up Docker by running: `docker-compose up`
1. Open a browser window and navigate to `http://localhost:3000/api/ping`
  1. _By completing the above step you have no verified that the **backend** is up and running._ 🎉
1. To verify that the **frontend** is running, navigate to `http://localhost:3001/register`
1. To complete setup, create a new user. The information you provide is yours to choose.
1. Additional notes:
  1. To run this process again: `docker-compose up` in a terminal inside your project directory
  1. To run commands on a running container: `docker exec`