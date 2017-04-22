# npmdoc-redux-async-connect

#### api documentation for  [redux-async-connect (v1.0.0-rc4)](https://github.com/Rezonans/redux-async-connect)  [![npm package](https://img.shields.io/npm/v/npmdoc-redux-async-connect.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-redux-async-connect) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redux-async-connect.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redux-async-connect)

#### It allows you to request async data, store them in redux state and connect them to your react component.

[![NPM](https://nodei.co/npm/redux-async-connect.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-async-connect)

- [https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-redux-async-connect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "redux-async-connect",
    "version": "1.0.0-rc4",
    "description": "It allows you to request async data, store them in redux state and connect them to your react component.",
    "main": "lib/index.js",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/Rezonans/redux-async-connect.git"
    },
    "scripts": {
        "build": "babel ./modules -d lib --ignore '__tests__'",
        "lint": "eslint modules",
        "start": "babel-node example/server.js",
        "test": "npm run lint && karma start",
        "prepublish": "node ./npm-scripts/postinstall.js"
    },
    "keywords": [
        "redux",
        "react",
        "connect",
        "async",
        "props"
    ],
    "author": "Rodion Salnik (http://brocoders.com)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Rezonans/redux-async-connect/issues"
    },
    "homepage": "https://github.com/Rezonans/redux-async-connect",
    "peerDependencies": {
        "react": "0.14.x",
        "react-router": "2.x.x",
        "react-redux": "4.x.x"
    },
    "devDependencies": {
        "babel-cli": "^6.4.5",
        "babel-core": "^6.4.5",
        "babel-eslint": "^5.0.0-beta6",
        "babel-loader": "^6.2.1",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babel-preset-stage-0": "^6.3.13",
        "eslint": "1.4.1",
        "eslint-config-rackt": "1.0.0",
        "eslint-plugin-react": "3.3.2",
        "expect": "^1.12.0",
        "express": "^4.13.3",
        "gzip-size": "^3.0.0",
        "history": "^1.13.1",
        "karma": "^0.13.3",
        "karma-browserstack-launcher": "^0.1.3",
        "karma-chrome-launcher": "^0.2.0",
        "karma-firefox-launcher": "^0.1.6",
        "karma-mocha": "^0.2.0",
        "karma-mocha-reporter": "^1.0.4",
        "karma-sourcemap-loader": "^0.3.5",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.0.1",
        "pretty-bytes": "^2.0.1",
        "react": "^0.14.2",
        "react-dom": "^0.14.2",
        "react-router": "2.0.0-rc5",
        "rimraf": "^2.4.2",
        "webpack": "^1.12.6",
        "webpack-dev-middleware": "^1.2.0",
        "eslint-config-airbnb": "^3.1.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
