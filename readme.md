# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

step 1: Install Docker
Step 2: Run the command docker-compose -v or docker-compose -version to check if docker-compose is correctly installed on your system.
step 3: Change the directory to where Anythink Market repo is located and open the terminal or bash in that folder.
step 4: Run the command docker-compose up. This will start composing the docker containers from the yaml files. All the images will get automatically pulled from the docker hub if not persent on your local system.
step 5: After composing go to http://localhost:3000/api/ping in your local web browser. If see a msg ({"msg":"Pong! Seems like Everythink is working, great job!"}) that means everything is working correctly.
step 6: Now follow the further instructions.