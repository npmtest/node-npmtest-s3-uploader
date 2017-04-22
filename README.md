# npmtest-s3-uploader

#### basic test coverage for  [s3-uploader (v2.0.3)](https://github.com/Turistforeningen/node-s3-uploader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-s3-uploader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-s3-uploader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-s3-uploader.svg)](https://travis-ci.org/npmtest/node-npmtest-s3-uploader)

#### Resize, rename, and upload images to AWS S3

[![NPM](https://nodei.co/npm/s3-uploader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/s3-uploader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-s3-uploader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-s3-uploader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-s3-uploader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-s3-uploader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-s3-uploader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-s3-uploader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-s3-uploader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-s3-uploader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-s3-uploader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-s3-uploader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-s3-uploader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-s3-uploader/build/test-report.html](https://npmtest.github.io/node-npmtest-s3-uploader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-s3-uploader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-s3-uploader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-s3-uploader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-s3-uploader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-s3-uploader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-s3-uploader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-s3-uploader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-s3-uploader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Den Norske Turistforening",
        "url": "DNT"
    },
    "bugs": {
        "url": "https://github.com/Turistforeningen/node-s3-uploader/issues"
    },
    "contributors": [
        {
            "name": "Håvard Ranum"
        },
        {
            "name": "Hans Kristian Flaatten"
        },
        {
            "name": "Anthony Ringoet"
        },
        {
            "name": "Luiz Freneda"
        },
        {
            "name": "Oleksii Sribnyi"
        }
    ],
    "dependencies": {
        "async": "^2.0.0",
        "aws-sdk": "^2.4.1",
        "im-metadata": "^3.0.0",
        "im-resize": "^2.3.1",
        "uuid": "^3.0.0"
    },
    "description": "Resize, rename, and upload images to AWS S3",
    "devDependencies": {
        "@starefossen/rand-path": "^2.0.0",
        "codacy-coverage": "^2.0.0",
        "eslint": "^3.3.1",
        "eslint-config-airbnb-base": "^10.0.1",
        "eslint-plugin-import": "^2.2.0",
        "greenkeeper-postpublish": "^1.0.0",
        "istanbul": "^0.4.3",
        "mocha": "^3.0.0",
        "nsp": "^2.4.0",
        "semantic-release": "^4.3.5"
    },
    "directories": {},
    "dist": {
        "shasum": "434fdf3a4c3ac07dae1459698fc0fbffb94ed995",
        "tarball": "https://registry.npmjs.org/s3-uploader/-/s3-uploader-2.0.3.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "a08a633da22e1620a4af9cdeb05dfddc9d4e0437",
    "homepage": "https://github.com/Turistforeningen/node-s3-uploader#readme",
    "keywords": [
        "aws",
        "s3",
        "imagemagic",
        "image",
        "resize",
        "rename",
        "upload",
        "versions"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "turistforeningen"
        }
    ],
    "name": "s3-uploader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Turistforeningen/node-s3-uploader.git"
    },
    "scripts": {
        "codacy-coverage": "codacy-coverage",
        "cover": "istanbul cover --report lcovonly ./node_modules/.bin/_mocha -- -r test/support/env test/**",
        "greenkeeper-postpublish": "greenkeeper-postpublish",
        "lint": "eslint index.js test",
        "nsp": "nsp check",
        "semantic-release": "semantic-release",
        "start": "supervisor index.js",
        "test": "mocha -b -c --check-leaks -R tap -r test/support/env test/**",
        "test:watch": "mocha -w -b -c --check-leaks -R progress -r test/support/env test/**"
    },
    "version": "2.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
