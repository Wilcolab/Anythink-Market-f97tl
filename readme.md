# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone/download the project
2. to verify your installation, execute the following commands in command line / Powershell `docker -v` and `docker-compose -v`.
3. in the folder root, run the command docker-compose up. This will setup docker and download any necessary files to run the app.
4. navigate to `http://localhost:3000/api/ping` to check if the docker image installed correctly
5. Finally, Create an account by going to `http://localhost:3000/register` set a username of of your own liking, E-mail address and password.

You should now have a fully working installation of the Anythink Market app.
