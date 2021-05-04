# Getting started
*Prerequisites: To run this project locally, you need to have [Nodejs](https://nodejs.org/) and [Docker](https://docs.docker.com/get-docker/) installed on your operating system*

**Install dependencies**
```
npm install
```

**Start MySQL via Docker**
```
docker-compose up
```

**Run migrations**
```
npm run migration:run
```

**Start both server (api) and client (conduit) apps**
```
npm run serve:api-conduit
```

**Open your browser at [http://localhost:4200](http://localhost:4200)**

You can now register a new account on your own to login and explore other funtionalities like create/update articles, update profile information, favorite articles, follow other users,... 

**Swagger**

Here is the [link](https://node-express-conduit.appspot.com/) to an another deployed service's Swagger

NOTE - Swagger might be outdated as it for another service
