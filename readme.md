# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## How to run locally?

1. [Install Docker](https://docs.docker.com/get-docker/)
2. [Install Docker Compose](https://docs.docker.com/compose/install/)
3. Run `docker-compose up`.

## First setup

> Replace the values between the brackets with the correct link address.

To setup this project you may choose one of the following paths:

- **Clone Repository**
  
1. If project is already setup, you can jump to step 4.
2. Clone the project. You can find the project in [this](https://github.com/ObelusFamily/Anythink-Market-zsobrsh7) repository.
3. Install [docker](https://docs.docker.com/get-docker/). If already installed move to the next step.
4. Run `docker-compose up` in the terminal to load the backend and frontend.
5. Test the backend server by pointing your browser to `[Backend Port]/api/ping`.
6. Check the frontend by creating a new user or logging in.
   1. To create a new user access the following link `[Frontend Port]/register`.
   2. To log in access the following link `[Frontend Port]/?` and use the following credentials:
      - Username: Bob
      - Password: pass123
      - Email: bob_test@wilco.com
7. Use `docker exec` in the terminal to run docker commands.
8. Repeat step 4 to resume the project in future use.

- **Github Codespace**

1. If project is already setup, open codespace and jump to step 3.
2. Create a Codespace by going to project repository. You can find the project repository [here](https://github.com/ObelusFamily/Anythink-Market-zsobrsh7).
3. Run `docker-compose up` in the codespace's terminal to load the backend and frontend.
4. Test the backend server by pointing your browser to `[Backend Port]/api/ping`.
5. Check the frontend by creating a new user or logging in.
   1. To create a new user access the following link `[Frontend Port]/register`.
   2. To log in access the following link `[Frontend Port]/?` and use the following credentials:
      - Username: Bob
      - Password: pass123
      - Email: bob_test@wilco.com
6. Use `docker exec` in the terminal to run docker commands.
7. Repeat step 3 to resume the project in future use.
