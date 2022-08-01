# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

First Steps:

```
git clone https://github.com/ObelusFamily/Anythink-Market-vyfs4.git
cd Anythink-Market-vyfs4
```
## Install Docker

You can install it from here - (Docker)[https://docs.docker.com/get-docker/]

## Verify the Installation of Docker

```
docker -v
docker-compose -v

```

## Run the project locally using Docker
 Go to your root directory and type:
 ```
 docker-compose up
 ```
 
 To check the project working fine, redirect your browser to [http://localhost:3000/api/ping]
