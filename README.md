# Game of Drones

This is a version of Rock Paper Scissors using angular 5, node, express and mongo

## Requirements

- Nodejs (Tested in version: 8.9.0)
- npm (Tested in version: 5.5.1)
- mongodb (Tested in version: 3.4.10)
- Chrome (62) or firefox (56)

## Execute

After install npm packages (`npm run prod`), run `npm run prod` or `npm start` to execute the app. Navigate to [http://localhost:9000/](http://localhost:9000/).

Is necessary to have installed [mongodb](https://www.mongodb.com) and it should be running in port 27017 without users. You can configure the env variable `PROD_MONGODB` or `MONGODB_URI` to use your current mongodb configuration. The variable should follow the next structure: `PROD_MONGODB=mongodb://dbuser:dbpass@host1:port1,host2:port2/dbname`

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Example page in Heroku

[https://u-game-of-drones.herokuapp.com](https://u-game-of-drones.herokuapp.com)
