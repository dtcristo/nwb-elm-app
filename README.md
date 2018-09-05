# nwb-elm-app

**DEPRICATED: nwb-elm-app is no-longer supported. Use [create-elm-app](https://github.com/halfzebra/create-elm-app) instead.**

An empty Elm project, with all the tools required for production builds. [nwb](https://github.com/insin/nwb) provides a wrapper around [Webpack](https://webpack.js.org/) (and other tools) that limits the amount of config and boilerplate needed.

This template includes many built in features for your convenience, without the need for configuration:
  * [elm-test](https://github.com/elm-community/elm-test) for Elm unit and fuzz testing.
  * [PostCSS](http://postcss.org/) for modern CSS today.
  * [Babel](https://babeljs.io/) for modern JavaScript today.
  * Development server with live reload.
  * Minification of JavaScript and CSS in builds.
  * Many more, see [here](https://github.com/insin/nwb/blob/master/docs/Features.md) for the nwb feature listing.

## How to use

Get [yarn](https://yarnpkg.com/en/docs/install).

Install dependencies with:
```
$ yarn
```

Write your Elm in `src` and run the development server:
```
$ yarn start
```
Vist [localhost:3000](http://localhost:3000/) to see the results.

Write tests in `tests` and run them:
```
$ yarn test
```

Run the tests automatically on file changes with:
```
$ yarn test:watch
```

For a production build run:
```
$ yarn build
```
Built assets will be output to `dist`.

## Credits
* Thanks [insin](https://github.com/insin) for [nwb](https://github.com/insin/nwb).
* Thanks [BurntCaramel](https://github.com/BurntCaramel) for this [article](https://medium.com/the-tech-bench/easy-elm-webpack-2-with-nwb-3ef5c5fde435).
