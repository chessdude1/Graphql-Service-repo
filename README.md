# Graphql Service

## Service powered with Node v16.11.0, npm, apollo-server

## To run app you need globaly install Typescript, and Docker
`npm -i -g yarn, typescript`


## How to start
You have two ways how start app
1. Using bash console(git)
  - Root directory of monorepo contains 3 bash scripts
  - Open new bash console -> write ```bash startMongoDataBase.sh``` 
  - Open new bash console -> write ```bash startDevMicroServices.sh```
  - Open new bash console -> write ```bash startDevGraphQlService.sh```

2. Manualy(using any console)
  - cd node-graphql-service; docker compose up;
  - cd node-graphql-service; npm i; npm run run:all:dev;
  - cd nest-graphql; npm i; npm run start:dev;

## Authorization
After authorization you will need add authorization token. Apollo studio has a tab for headers.