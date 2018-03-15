
# Express-Boilerplate

A fast :fast_forward:, simple **Node.js/Express** + **MongoDB** + **Vue.js** web app boilerplate project. This template provides a set of best-practice setups and avoids common mistakes. Hopefully useful for hackathons... :pray: :zap: 

## Quickstart

```
$ git clone https://github.com/cktang88/express-boilerplate
$ cd express-boilerplate
$ npm i --dev
$ npm start
```
Then go visit http://localhost:8000

## Batteries included.

### Back-end
* [x] **[Express](https://github.com/expressjs/express)** - Web framework for Node.js
* [x] **[MongoDB](https://github.com/mongodb/node-mongodb-native)** - Database for fast prototyping
* [x] [Bunyan](https://github.com/trentm/node-bunyan) - Easy JSON logging.

### Front-end
* [x] **[Vue.js](https://vuejs.org/)**
* [x] [Spectre.css](https://picturepan2.github.io/spectre/index.html) - lightweight CSS-only framework that uses native HTML tags. A third the size of Bulma.css, a quarter the size of Bootstrap css.
### Extra
* [x] [Eslint](http://eslint.org/) - Javascript linting
* [x] [node-fetch](https://github.com/bitinn/node-fetch) - server-side HTTP requests using browser `window.fetch()` api
* [x] Security via [CORS](https://github.com/expressjs/cors) and [Helmet.js](https://helmetjs.github.io/)
* [x] [node-dev](https://github.com/fgnass/node-dev) - Automatic server reload

## Philosophy
1. **Fast** - get up and running immediately.
2. **Simple, zero-config** - no need to manually set up config files.
3. **Lightweight, no module bloat** - total node_modules size is just 20MB.

## Project structure
```
.
├── logs // where logs get stored
├── public
│   ├── domhelpers.js // for DOM manipulation, mimics jQuery
│   ├── index.html
│   └── index.js
├── server
│   ├── dbManager.js // interacting with MongoDB
│   ├── logger.js // simple logging functionality
│   └── server.js // main Express server
└── tests // put tests in here
```

## Dev
Code linting with [AirBnB's style guide](https://github.com/airbnb/javascript):
```
$ npm run lint
```

## License

This work is licensed under the [The MIT License](http://opensource.org/licenses/MIT)
