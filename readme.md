# Welcome to the Anythink Market repo

---

Anythink is Market hub for creating and consuming feeds. It lets you choose your interest niche and deliver feeds according to your interests.
[![Reactjs](https://reactjs.org/logo-og.png)](https://reactjs.org)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://app.wilco.gg)

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

### Installation

---

- Clone the repo
  ```sh
  git clone git@github.com:ObelusFamily/Anythink-Market-p5ixs.git
  ```
- Install docker on your system

  ```sh
  # For Ubuntu Users
   sudo apt-get update
   sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin
  # For more detailed steps visit https://docs.docker.com/engine/install/
  ```

- Create the build using docker-compose in root directory of repo
  ```sh
   docker-compose build
  ```
- Verify the docker images
  ```sh
    docker images
  ```
- Spin up the containers

  ```sh
     docker-compose up
  ```

- If docker successfully started then verify the deployment by navigating to your server address in your preferred browser.

  ```sh
  # frontend
  https://localhost:3001
  #backend
  https://localhost:3000/api/ping
  ```

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

#### Development

---

When implementing a new feature or fixing a bug, please create a new pull request against main from a feature/bug branch and add **@vanessa-cooper** as reviewer.

### Tech

---

Anythink uses a below tech stack:

- [Reactjs](https://reactjs.org) - Blazing Fast UI!
- [node.js](https://nodejs.org) - evented I/O for the backend
- [Express](https://expressjs.com) - fast node.js network app framework
- [Docker](https://docker.com) - Easy to setup

#### Copyrights

---

[**&copy; Wilco Anythink 2022**](https://app.wilco.gg/)
