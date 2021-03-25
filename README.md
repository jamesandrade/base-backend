<h3 align="center">
  Base backend for my api's
</h3>

## 💻 Getting started

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)
- One instance of database
> Obs.: I recommend use docker

**Clone the project and access the folder**

```bash
$ git clone https://github.com/jamesandrade/base-backend && cd BASE-BACKEND
```

**Follow the steps below**

```bash
# Install the dependencies
$ yarn

# eslint config
$ yarn eslint --init

# step 1
- To check syntax, find problems and enforce code style

# step 2
- To check syntax, find problems and enforce code style

# step 3
- None of these

# step 4
- No

# step 5
- Node

# step 6
- Use a popular style guide

# step 7 
- Airbnb

# step 8
- JSON

# Make a copy of 'ormconfig.example.json' to 'ormconfig.json'
$ cp ormconfig.example.json ormconfig.json

# Once the services are running, run the migrations
$ yarn typeorm migration:run

# To finish, run the api service
$ yarn dev:server

# Well done, project is started!
```
