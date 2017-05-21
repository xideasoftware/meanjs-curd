This project do simple CURD operation with Angular2 UI.

Technologies/libraries used in this project:
* [**M**ongoose.js](http://www.mongoosejs.com) ([MongoDB](https://www.mongodb.com)): database
* [**E**xpress.js](http://expressjs.com): backend framework
* [**A**ngular 2](https://angular.io): frontend framework
* [**N**ode.js](https://nodejs.org): runtime environment


## Prerequisites
1. Install [Node.js](https://nodejs.org) and [MongoDB](https://www.mongodb.com)
2. Install Angular CLI: `npm i -g @angular/cli`
3. From project root folder install all the dependencies: `npm i`

## Run
1. Command window 1: `mongod`: run MongoDB
2. Command window 2: `npm run server`: run Express backend server (with autoreload)
3. Command window 3: `npm start`: run Angular frontend (with autobuild and autoreload)
4. Browser will automatically open to: [localhost:4200](http://localhost:4200)

## Production
Run `npm run prod` to run frontend with a production ready bundle.