# npmtest-template

#### basic test coverage for  [template (v0.17.5)](https://github.com/jonschlinkert/template)  [![npm package](https://img.shields.io/npm/v/npmtest-template.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-template) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-template.svg)](https://travis-ci.org/npmtest/node-npmtest-template)

#### Render templates using any engine. Supports, layouts, pages, partials and custom template types. Use template helpers, middleware, routes, loaders, and lots more. Powers assemble, verb and other node.js apps.

[![NPM](https://nodei.co/npm/template.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/template)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-template/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-template/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-template/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-template/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-template/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-template/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-template/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-template/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-template/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-template/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-template/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-template/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-template/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-template/build/test-report.html](https://npmtest.github.io/node-npmtest-template/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-template/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-template/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-template/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-template/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-template/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-template/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-template/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-template/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "bugs": {
        "url": "https://github.com/jonschlinkert/template/issues"
    },
    "dependencies": {
        "arr-flatten": "^1.0.1",
        "array-sort": "^0.1.1",
        "assign-value": "^0.1.2",
        "async-each": "^0.1.6",
        "clone-deep": "^0.2.3",
        "collection-visit": "^0.2.1",
        "component-emitter": "^1.2.0",
        "copy": "^0.1.2",
        "dashify": "^0.2.0",
        "define-property": "^0.2.5",
        "delegate-properties": "^0.3.0",
        "detect-conflicts": "^0.1.1",
        "en-route": "^0.7.3",
        "engine-cache": "^0.16.1",
        "export-files": "^2.1.0",
        "extend-shallow": "^2.0.1",
        "filter-values": "^0.4.0",
        "for-in": "^0.1.4",
        "for-own": "^0.1.3",
        "get-value": "^2.0.0",
        "group-array": "^0.3.0",
        "has-values": "^0.1.3",
        "helper-cache": "^0.7.2",
        "inflection": "^1.7.2",
        "is-extendable": "^0.1.1",
        "is-glob": "^2.0.1",
        "kind-of": "^2.0.1",
        "layouts": "^0.10.6",
        "lazy-cache": "^0.2.4",
        "load-templates": "^0.8.8",
        "loader-cache": "^0.6.1",
        "matched": "^0.3.2",
        "micromatch": "^2.3.11",
        "mixin-object": "^2.0.1",
        "object.omit": "^2.0.0",
        "object.pick": "^1.1.1",
        "object.reduce": "^0.1.7",
        "parse-filepath": "^0.6.3",
        "recent": "^0.1.0",
        "relative": "^3.0.1",
        "relative-dest": "^0.1.0",
        "rewrite-ext": "^0.2.0",
        "set-value": "^0.3.0",
        "sort-object": "^3.0.0",
        "write": "^0.2.1"
    },
    "description": "Render templates using any engine. Supports, layouts, pages, partials and custom template types. Use template helpers, middleware, routes, loaders, and lots more. Powers assemble, verb and other node.js apps.",
    "devDependencies": {
        "ansi-green": "^0.1.1",
        "ansi-red": "^0.1.1",
        "async": "^1.5.0",
        "bluebird": "^3.0.2",
        "consolidate": "^0.13.1",
        "engine-handlebars": "^0.8.0",
        "engine-lodash": "^0.8.2",
        "event-stream": "^3.3.2",
        "glob-fs": "^0.1.6",
        "glob-parent": "^2.0.0",
        "iterator-async": "^0.1.1",
        "iterator-promise": "^0.1.1",
        "iterator-sync": "^0.1.1",
        "lodash": "^3.10.1",
        "mocha": "^2.3.3",
        "once": "^1.3.2",
        "parser-front-matter": "^1.3.0",
        "should": "^7.1.1",
        "success-symbol": "^0.1.0",
        "swig": "^1.4.2",
        "through2": "^2.0.0",
        "vinyl": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5c3b751dc46eb834d6f7e3c97b34e4ccf1bfda0e",
        "tarball": "https://registry.npmjs.org/template/-/template-0.17.5.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "a385ec61371fb335b5dc2692d631e667a7692af2",
    "homepage": "https://github.com/jonschlinkert/template",
    "keywords": [
        "atpl",
        "coffee",
        "compile",
        "consolidate",
        "dot",
        "dust",
        "dustjs",
        "dustjs-helpers",
        "dustjs-linkedin",
        "eco",
        "ect",
        "ejs",
        "engine",
        "engines",
        "express",
        "haml",
        "haml-coffee",
        "hamljs",
        "handlebars",
        "helpers",
        "hogan.js",
        "jade",
        "jazz",
        "jqtpl",
        "liquor",
        "lo-dash",
        "lodash",
        "markdown",
        "mote",
        "mustache",
        "nunjucks",
        "process",
        "qejs",
        "ractive",
        "render",
        "swig",
        "template",
        "templates",
        "templayed",
        "toffee",
        "underscore",
        "view",
        "walrus",
        "whiskers",
        "yaml"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert"
        },
        {
            "name": "doowb"
        }
    ],
    "name": "template",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonschlinkert/template.git"
    },
    "scripts": {
        "ci": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "cover": "istanbul cover node_modules/.bin/_mocha && open coverage/lcov-report/index.html",
        "test": "mocha"
    },
    "verb": {
        "related": {
            "list": [
                "layouts",
                "en-route",
                "assemble",
                "verb"
            ]
        }
    },
    "version": "0.17.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
