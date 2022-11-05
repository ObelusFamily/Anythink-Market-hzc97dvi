# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

-   After cloning the repository, install Docker in your machine by following the steps given in this [link](https://docs.docker.com/get-docker/)
-   Check if docker is properly installed by running `docker -v` and `docker-compose -v` in your command terminal.
-   Run the command `docker-compose up` from the root directory of the cloned repository to load the frontend, backend, and the database.
-   Now your environment is ready and it can be verified by pointing your browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping).
