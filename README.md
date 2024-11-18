# ZenRace - API
## Project
ZenRace is a project that was conducted in the context of a mentored project during our final year of the Bachelor in Computer Science at the IUT Nord Franche-Comté. The main objective of this project is to developp a complete IOT system that allows to manage a running race. This system is composed of several parts:
- A REST API that allows to manage the data of the project.
- A web application that allows to manage
- A mobile application that allows spectators to follow the race and share photos of the event.
- A set of IOT devices that allow to get the data of the race.

## Description
**This repository contains the API part of the project.** It is a REST API that allows to manage the data of the ZenRace project. It is developed in JavaScipt with the Node.js engine and the Express.js library.

## Installation
### Prerequisites
- Node.js
- npm
- MongoDB

All the dependancies are listed in the `package.json` file. You can install them by running the following command:
```bash
npm install
```

> **Note:** The API is configured to connect to a MongoDB database on the `localhost` server. You can change the connection settings in environment variables or in the `config.js` file. (See the [Configuration](#configuration) section)

## Configuration
The configuration of the API is done in environment variables. You can create a `.env` file at the root of the project and define the following variables:
- `EXPRESS_PORT`: The port on which the API will listen.
- `MONGODB_URI`: The URI of the MongoDB database.
- ...

## Usage
To start the API, you can run the following command:
```bash
npm start
```

## Documentation
