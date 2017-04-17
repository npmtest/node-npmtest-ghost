# test coverage for  [ghost (v0.11.7)](http://ghost.org)  [![npm package](https://img.shields.io/npm/v/npmtest-ghost.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ghost) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ghost.svg)](https://travis-ci.org/npmtest/node-npmtest-ghost)
#### Just a blogging platform.

[![NPM](https://nodei.co/npm/ghost.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ghost)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ghost/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ghost/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ghost/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ghost/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ghost/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ghost/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ghost/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ghost/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ghost/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ghost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ghost/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ghost/build/test-report.html](https://npmtest.github.io/node-npmtest-ghost/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ghost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ghost/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ghost/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ghost/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ghost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ghost/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ghost/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ghost/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ghost Foundation"
    },
    "bugs": {
        "url": "https://github.com/TryGhost/Ghost/issues"
    },
    "contributors": "https://github.com/TryGhost/Ghost/graphs/contributors",
    "dependencies": {
        "amperize": "0.3.4",
        "archiver": "1.3.0",
        "bcryptjs": "2.4.3",
        "bluebird": "3.4.7",
        "body-parser": "1.16.0",
        "bookshelf": "0.10.2",
        "chalk": "1.1.3",
        "cheerio": "0.22.0",
        "compression": "1.6.2",
        "connect-slashes": "1.3.1",
        "cookie-session": "1.2.0",
        "cors": "2.8.1",
        "csv-parser": "1.11.0",
        "downsize": "0.0.8",
        "express": "4.14.1",
        "express-hbs": "1.0.4",
        "extract-zip-fork": "1.5.1",
        "fs-extra": "2.0.0",
        "ghost-gql": "0.0.6",
        "glob": "5.0.15",
        "gscan": "0.2.0",
        "html-to-text": "3.1.0",
        "image-size": "0.5.1",
        "intl": "1.2.5",
        "intl-messageformat": "1.3.0",
        "jsonpath": "0.2.9",
        "knex": "0.12.5",
        "lodash": "4.17.4",
        "moment": "2.17.1",
        "moment-timezone": "0.5.9",
        "morgan": "1.7.0",
        "multer": "1.3.0",
        "mysql": "2.1.1",
        "netjet": "1.1.3",
        "nodemailer": "0.7.1",
        "oauth2orize": "1.7.0",
        "passport": "0.3.2",
        "passport-http-bearer": "1.0.1",
        "passport-oauth2-client-password": "0.1.2",
        "path-match": "1.2.4",
        "pg": "6.1.2",
        "rss": "1.2.2",
        "sanitize-html": "1.14.1",
        "semver": "5.3.0",
        "showdown-ghost": "0.3.6",
        "sqlite3": "3.1.8",
        "superagent": "3.4.1",
        "unidecode": "0.1.8",
        "uuid": "3.0.0",
        "validator": "6.2.1",
        "xml": "1.0.1"
    },
    "description": "Just a blogging platform.",
    "devDependencies": {
        "grunt": "1.0.1",
        "grunt-bg-shell": "2.3.3",
        "grunt-cli": "1.2.0",
        "grunt-contrib-clean": "1.0.0",
        "grunt-contrib-compress": "1.3.0",
        "grunt-contrib-copy": "1.0.0",
        "grunt-contrib-jshint": "1.0.0",
        "grunt-contrib-uglify": "2.0.0",
        "grunt-contrib-watch": "1.0.0",
        "grunt-docker": "0.0.11",
        "grunt-express-server": "0.5.3",
        "grunt-jscs": "3.0.1",
        "grunt-mocha-cli": "2.1.0",
        "grunt-mocha-istanbul": "5.0.2",
        "grunt-shell": "1.3.1",
        "grunt-subgrunt": "1.2.0",
        "grunt-update-submodules": "0.4.1",
        "istanbul": "0.4.5",
        "matchdep": "1.0.1",
        "mocha": "3.1.2",
        "nock": "9.0.4",
        "rewire": "2.5.2",
        "should": "11.2.0",
        "should-http": "0.1.0",
        "sinon": "1.17.7",
        "supertest": "3.0.0",
        "tmp": "0.0.31"
    },
    "directories": {},
    "dist": {
        "shasum": "d1da9614e4abd047ae55b862366822257bc4a159",
        "tarball": "https://registry.npmjs.org/ghost/-/ghost-0.11.7.tgz"
    },
    "engines": {
        "node": "^4.2.0 || ^6.9.0"
    },
    "greenkeeper": {
        "ignore": [
            "glob",
            "mysql",
            "nodemailer",
            "pg",
            "showdown-ghost"
        ]
    },
    "homepage": "http://ghost.org",
    "keywords": [
        "ghost",
        "blog",
        "cms"
    ],
    "license": "MIT",
    "main": "./core/index",
    "maintainers": [
        {
            "name": "erisds"
        },
        {
            "name": "johnonolan"
        },
        {
            "name": "kevinansfield"
        },
        {
            "name": "kirrg001"
        }
    ],
    "name": "ghost",
    "optionalDependencies": {
        "mysql": "2.1.1",
        "pg": "6.1.2"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/TryGhost/Ghost.git"
    },
    "scripts": {
        "preinstall": "node core/server/utils/npm/preinstall.js",
        "start": "node index",
        "test": "grunt validate --verbose"
    },
    "version": "0.11.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
