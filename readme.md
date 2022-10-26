# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
To use the app you need to have [docker installed](https://docs.docker.com/get-docker/)

To verify that you have docker ready by running the following commands in the terminal `docker -v` and `docker-compose -v`

Then from the project root directory run `docker-compose up` to load the frontend and backend. if docker is running you should be able to run [http://localhost:3000/api/ping](http://localhost:3000/api/ping) from your browser.

To confirm that the frontend is running and connected to the backend try creating a user on [http://localhost:3001/register](http://localhost:3001/register)




Once you have that running you are ready to start something amazing! and next time you want to start the application you can run `docker-compose up` in you terminal. You can also use `docker exec ` to run commands on a running container.

