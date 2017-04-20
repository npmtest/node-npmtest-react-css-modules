# npmtest-react-css-modules

#### basic test coverage for  [react-css-modules (v4.2.0)](https://github.com/gajus/react-css-modules#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-css-modules.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-css-modules) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-css-modules.svg)](https://travis-ci.org/npmtest/node-npmtest-react-css-modules)

#### Seamless mapping of class names to CSS modules inside of React components.

[![NPM](https://nodei.co/npm/react-css-modules.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-css-modules)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-css-modules/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-css-modules/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-css-modules/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-css-modules/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-css-modules/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-css-modules/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-css-modules/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-css-modules/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-css-modules/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-css-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-css-modules/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-css-modules/build/test-report.html](https://npmtest.github.io/node-npmtest-react-css-modules/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-css-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-css-modules/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-css-modules/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-css-modules/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-css-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-css-modules/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-css-modules/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-css-modules/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gajus Kuizinas",
        "url": "http://gajus.com"
    },
    "bugs": {
        "url": "https://github.com/gajus/react-css-modules/issues"
    },
    "dependencies": {
        "hoist-non-react-statics": "^1.2.0",
        "lodash": "^4.16.6",
        "object-unfreeze": "^1.1.0"
    },
    "description": "Seamless mapping of class names to CSS modules inside of React components.",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-lodash": "^3.2.9",
        "babel-plugin-transform-proto-to-assign": "^6.9.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-register": "^6.18.0",
        "chai": "^4.0.0-canary.1",
        "eslint": "^3.10.0",
        "eslint-config-canonical": "^5.5.0",
        "husky": "^0.11.9",
        "jsdom": "^9.8.3",
        "mocha": "^3.1.2",
        "react": "^15.4.0-rc.4",
        "react-addons-shallow-compare": "^15.4.0-rc.4",
        "react-addons-test-utils": "^15.4.0-rc.4",
        "react-dom": "^15.4.0-rc.4",
        "semantic-release": "^6.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "21acd0c0e59cb37ccb79bcf0013a1fd05a246e50",
        "tarball": "https://registry.npmjs.org/react-css-modules/-/react-css-modules-4.2.0.tgz"
    },
    "gitHead": "b5d84c16027d301edbbc28103bab9792dfd01ebb",
    "homepage": "https://github.com/gajus/react-css-modules#readme",
    "keywords": [
        "react-component",
        "react",
        "css",
        "modules"
    ],
    "license": "BSD-3-Clause",
    "main": "./dist/",
    "maintainers": [
        {
            "name": "gajus"
        }
    ],
    "name": "react-css-modules",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gajus/react-css-modules.git"
    },
    "scripts": {
        "build": "NODE_ENV=production babel ./src --out-dir ./dist",
        "lint": "eslint ./src ./tests",
        "precommit": "npm run test",
        "test": "NODE_ENV=development mocha --compilers js:babel-register ./tests/**/*.js && npm run lint && npm run build"
    },
    "version": "4.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
