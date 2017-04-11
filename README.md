# test coverage for  [react-router-redux (v4.0.8)](https://github.com/reactjs/react-router-redux#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-router-redux.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-router-redux) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-router-redux.svg)](https://travis-ci.org/npmtest/node-npmtest-react-router-redux)
#### Ruthlessly simple bindings to keep react-router and redux in sync

[![NPM](https://nodei.co/npm/react-router-redux.png?downloads=true)](https://www.npmjs.com/package/react-router-redux)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-router-redux/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-router-redux/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-router-redux/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-router-redux/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-router-redux/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-router-redux/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-router-redux/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-router-redux/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-react-router-redux/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-router-redux/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-react-router-redux%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-router-redux/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-router-redux/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-react-router-redux%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-router-redux/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-router-redux/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-router-redux/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "James Long",
        "Tim Dorr"
    ],
    "bugs": {
        "url": "https://github.com/reactjs/react-router-redux/issues"
    },
    "dependencies": {},
    "description": "Ruthlessly simple bindings to keep react-router and redux in sync",
    "devDependencies": {
        "babel-cli": "^6.1.2",
        "babel-core": "^6.7.4",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.5.0",
        "babel-plugin-transform-es3-property-literals": "^6.5.0",
        "babel-polyfill": "^6.7.4",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.3.13",
        "babel-register": "^6.4.3",
        "eslint": "^3.15.0",
        "eslint-config-react-app": "^0.5.0",
        "eslint-plugin-flowtype": "^2.29.2",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.8.0",
        "expect": "^1.13.0",
        "history": "^3.0.0",
        "isparta": "^4.0.0",
        "isparta-loader": "^2.0.0",
        "karma": "^1.4.1",
        "karma-coverage": "^1.1.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.2",
        "karma-sourcemap-loader": "^0.3.5",
        "karma-webpack": "^2.0.2",
        "mocha": "^3.2.0",
        "react": "^15.4.2",
        "react-dom": "^15.4.2",
        "react-redux": "^5.0.2",
        "react-router": "^3.0.0",
        "redux": "^3.0.4",
        "redux-devtools": "^3.0.0",
        "redux-devtools-dock-monitor": "^1.0.1",
        "redux-devtools-log-monitor": "^1.0.1",
        "webpack": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "227403596b5151e182377dab835b5d45f0f8054e",
        "tarball": "https://registry.npmjs.org/react-router-redux/-/react-router-redux-4.0.8.tgz"
    },
    "files": [
        "*.md",
        "dist",
        "LICENSE",
        "lib",
        "src"
    ],
    "gitHead": "a2825ac0b8e34662624455ab98e29e2eb27f8096",
    "homepage": "https://github.com/reactjs/react-router-redux#readme",
    "keywords": [
        "react",
        "redux",
        "router"
    ],
    "license": "MIT",
    "main": "lib/index",
    "maintainers": [
        {
            "name": "jlongster",
            "email": "longster@gmail.com"
        },
        {
            "name": "timdorr",
            "email": "timdorr@timdorr.com"
        }
    ],
    "name": "react-router-redux",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/react-router-redux.git"
    },
    "scripts": {
        "build": "npm run build:commonjs & npm run build:umd & npm run build:umd:min",
        "build:commonjs": "mkdir -p lib && babel ./src -d lib",
        "build:umd": "webpack dist/ReactRouterRedux.js",
        "build:umd:min": "NODE_ENV=production webpack dist/ReactRouterRedux.min.js",
        "lint": "eslint examples src test",
        "prepublish": "npm run build",
        "test": "npm run lint && npm run test:node && npm run test:browser",
        "test:browser": "karma start",
        "test:cov": "npm run test:cov:browser && npm run test:cov:node && npm run test:cov:report",
        "test:cov:browser": "COVERAGE=true karma start",
        "test:cov:node": "babel-node $(npm bin)/isparta cover $(npm bin)/_mocha report --dir ./coverage/node-coverage -- --recursive ./test/node",
        "test:cov:report": "$(npm bin)/istanbul report --dir ./coverage --include **/*coverage.json html text",
        "test:node": "mocha --compilers js:babel-register --recursive ./test/*.spec.js"
    },
    "tags": [
        "react",
        "redux"
    ],
    "version": "4.0.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
