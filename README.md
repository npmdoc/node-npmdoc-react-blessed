# npmdoc-react-blessed

#### api documentation for  [react-blessed (v0.1.8)](https://github.com/yomguithereal/react-blessed#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-blessed.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-blessed) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-blessed.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-blessed)

#### A react renderer for blessed.

[![NPM](https://nodei.co/npm/react-blessed.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-blessed)

- [https://npmdoc.github.io/node-npmdoc-react-blessed/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-blessed/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-blessed/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-blessed/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-blessed/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-blessed/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-blessed",
    "version": "0.1.8",
    "description": "A react renderer for blessed.",
    "main": "./dist/render.js",
    "scripts": {
        "animation": "babel-node ./examples/animation.jsx",
        "build": "babel ./src --out-dir ./dist",
        "dashboard": "babel-node ./examples/dashboard.jsx",
        "demo": "babel-node ./examples/demo.jsx",
        "prepublish": "npm run build",
        "test": "mocha -R spec --compilers js:babel-register ./test/endpoint.js"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yomguithereal/react-blessed.git"
    },
    "keywords": [
        "blessed",
        "react",
        "renderer",
        "cli",
        "interface"
    ],
    "author": "yomguithereal",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/yomguithereal/react-blessed/issues"
    },
    "homepage": "https://github.com/yomguithereal/react-blessed#readme",
    "devDependencies": {
        "babel-cli": "^6.6.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.5.0",
        "babel-register": "^6.6.0",
        "blessed": "^0.1.81",
        "mocha": "^2.4.5",
        "react": "^0.14.7"
    },
    "dependencies": {
        "invariant": "^2.2.0",
        "lodash": "^3.x.x"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
