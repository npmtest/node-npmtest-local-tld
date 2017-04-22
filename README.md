# npmtest-local-tld

#### basic test coverage for  local-tld (v4.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-local-tld.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-local-tld) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-local-tld.svg)](https://travis-ci.org/npmtest/node-npmtest-local-tld)

#### Maintain a TLD on localhost for all your projects.

[![NPM](https://nodei.co/npm/local-tld.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/local-tld)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-local-tld/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-local-tld/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-local-tld/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-local-tld/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-local-tld/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-local-tld/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-local-tld/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-local-tld/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-local-tld/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-local-tld/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-local-tld/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-local-tld/build/test-report.html](https://npmtest.github.io/node-npmtest-local-tld/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-local-tld/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-local-tld/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-local-tld/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-local-tld/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-local-tld/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-local-tld/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-local-tld/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-local-tld/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "local-tld",
    "version": "4.0.0",
    "description": "Maintain a TLD on localhost for all your projects.",
    "main": "bin/local-tld-service",
    "dependencies": {
        "dnsserver": "https://github.com/sstephenson/dnsserver.js/archive/library.tar.gz",
        "watchfd": "~0.0.9",
        "http-proxy": "~0.8.7"
    },
    "devDependencies": {},
    "scripts": {
        "postinstall": "./bin/local-tld-setup",
        "preuninstall": "./bin/local-tld-uninstall"
    },
    "repository": "https://github.com:hoodiehq/local-tld",
    "keywords": [
        "tld",
        "pow"
    ],
    "os": [
        "darwin"
    ],
    "author": "Jan Lehnardt <jan@apache.org>",
    "license": "Apache 2.0",
    "readmeFilename": "README.md",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
