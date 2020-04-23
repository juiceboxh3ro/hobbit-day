# Node Server Testing Guided Project

Guided project for **Node Server Testing** Module.

## Project Setup

- [ ] fork and clone this repository.
- [ ] **CD into the folder** where you cloned **your fork**.
- [ ] type `npm i` to download dependencies.
- [ ] type `npm run server` to start the API.

Please follow along as the instructor adds automated tests to the API.

## Deploy to Heroku using PostgreSQL

- add the Heroku Postgress add-on (under settings) to the application on Heroku
- add the `pg` npm package
- configure the `production` property on knexfile.js to use `pg` and the `process.env.DATABASE_URL` variable as the connection