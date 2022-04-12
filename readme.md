# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.
download docker to you machine and clone the repository. then, in the repository's directory, use the command "docker-compose up" in the powershell (if you're a windows user) or the terminal. if everything is working correctly, you'll be able to go to localhost:3000/api/ping and move on! it might take a few minutes for it to boot.
finally, if everything is working properly, you’ll be able to create a new user on localhost:3001/register.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
