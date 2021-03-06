[![CircleCI](https://circleci.com/gh/r-park/soundcloud-redux.svg?style=shield&circle-token=f1dddd8dfa05f08655f30b7d7451d23360f63652)](https://circleci.com/gh/r-park/soundcloud-redux)


# SoundCloud Redux

A basic SoundCloud API client built with React, Redux, and Redux Saga. Try the [live demo](https://soundcloud-redux.herokuapp.com).

![screenshot](http://i.imgur.com/nylCI4T.png)


Stack
-----

- React
- React Hot Loader `3.0.0-beta.5`
- React Redux
- React Router
- Redux Saga
- RxJS
- Immutable
- Ava
- Babel
- Circle CI
- Express
- Heroku
- Karma
- Superagent
- Webpack `2.1.0-beta.25`
- Webpack Dev Server `2.1.0-beta.4`


Quick Start
-----------

```shell
$ git clone https://github.com/r-park/soundcloud-redux.git
$ cd soundcloud-redux
$ npm install
$ npm start
```


NPM Commands
------------

|Command|Description|
|---|---|
|npm start|Start webpack development server @ **localhost:3000**|
|npm run build|Build production bundles to **./target** directory|
|npm run server|Start express server @ **localhost:3000** to serve built artifacts from **./target** directory|
|npm test|Run tests and generate coverage report to **./coverage** directory|
|npm run test:watch|Run tests; watch for changes and re-run tests|
