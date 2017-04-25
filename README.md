# npmtest-vorlon

#### basic test coverage for  vorlon (v0.5.4)  [![npm package](https://img.shields.io/npm/v/npmtest-vorlon.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vorlon) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vorlon.svg)](https://travis-ci.org/npmtest/node-npmtest-vorlon)

#### vorlon

[![NPM](https://nodei.co/npm/vorlon.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vorlon)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vorlon/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vorlon/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vorlon/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vorlon/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vorlon/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-vorlon/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-vorlon/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vorlon/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vorlon/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vorlon/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vorlon/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vorlon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vorlon/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vorlon/build/test-report.html](https://npmtest.github.io/node-npmtest-vorlon/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vorlon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vorlon/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vorlon/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vorlon/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vorlon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vorlon/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vorlon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vorlon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "vorlon": "./bin/vorlon"
    },
    "dependencies": {
        "body-parser": "~1.12.3",
        "colors": "~1.1.2",
        "cookie-parser": "~1.3.5",
        "cookieparser": "~0.1.0",
        "cors": "^2.7.1",
        "express": "~4.12.3",
        "express-session": "~1.11.1",
        "favicon": "0.0.2",
        "http-proxy": "~1.11.2",
        "jade": "~1.9.2",
        "json": "~9.0.3",
        "method-override": "2.3.4",
        "minimist": "^1.2.0",
        "multer": "~0.1.8",
        "pageres": "^4.1.2",
        "passport": "~0.2.1",
        "passport-local": "~1.0.0",
        "passport-twitter": "~1.0.3",
        "socket.io": "^1.5.0",
        "stylus": "~0.50.0",
        "winston": "~1.0.1",
        "winston-azure": "0.0.4",
        "winston-logs-display": "~0.1.1",
        "xmlhttprequest": "~1.7.0"
    },
    "description": "vorlon",
    "devDependencies": {
        "gulp": "~3.9.1",
        "gulp-concat": "~2.2.0",
        "gulp-filter": "~0.4.1",
        "gulp-less": "~3.0.3",
        "gulp-mocha": "~2.2.0",
        "gulp-rename": "~1.2.0",
        "gulp-sourcemaps": "~1.5.2",
        "gulp-typescript": "~2.13.6",
        "gulp-uglify": "~0.3.0",
        "gulp-util": "~2.2.14",
        "gulp-webserver": "~0.9.0",
        "gulp-zip": "~3.0.2",
        "merge2": "~0.3.5",
        "mocha-junit-reporter": "^1.9.1",
        "through": "~2.3.4",
        "typescript": "^1.8.10"
    },
    "directories": {},
    "dist": {
        "shasum": "b949702291a742a879312afbf7f2832441b8903e",
        "tarball": "https://registry.npmjs.org/vorlon/-/vorlon-0.5.4.tgz"
    },
    "gitHead": "7be5ab5eb3852b1e54b87f63fc78fe7c908e5cfd",
    "main": "Server/server.js",
    "maintainers": [
        {
            "name": "vorlonjs"
        },
        {
            "name": "deltakosh"
        },
        {
            "name": "meulta"
        }
    ],
    "name": "vorlon",
    "optionalDependencies": {},
    "scripts": {
        "build": "node disclaimer.js && npm run build-all",
        "build-all": "gulp --gulpfile=./gulpfile.js",
        "global-deploy-gulp": "npm install -g gulp",
        "global-deploy-gulp-cli": "npm install -g gulp-cli",
        "prepublish": "npm run build",
        "start": "node ./Server/server.js"
    },
    "version": "0.5.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
