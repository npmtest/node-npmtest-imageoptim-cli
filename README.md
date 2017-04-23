# npmtest-imageoptim-cli

#### basic test coverage for  [imageoptim-cli (v1.14.9)](https://github.com/JamieMason/ImageOptim-CLI)  [![npm package](https://img.shields.io/npm/v/npmtest-imageoptim-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-imageoptim-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-imageoptim-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-imageoptim-cli)

#### Automates ImageOptim, ImageAlpha, and JPEGmini for Mac to make batch optimisation of images part of your automated build process.

[![NPM](https://nodei.co/npm/imageoptim-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imageoptim-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-imageoptim-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-imageoptim-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-imageoptim-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-imageoptim-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-imageoptim-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-imageoptim-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-imageoptim-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imageoptim-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imageoptim-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imageoptim-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-imageoptim-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "imageoptim-cli",
    "description": "Automates ImageOptim, ImageAlpha, and JPEGmini for Mac to make batch optimisation of images part of your automated build process.",
    "version": "1.14.9",
    "author": "Jamie Mason <siunmaru@gmail.com>",
    "bin": {
        "imageOptim": "bin/imageOptim",
        "imageOptimAppleScriptLib": "bin/imageOptimAppleScriptLib",
        "imageOptimBashLib": "bin/imageOptimBashLib",
        "pngquant": "bin/pngquant"
    },
    "bugs": "https://github.com/JamieMason/ImageOptim-CLI/issues",
    "contributors": [
        "Adam Kiss (https://github.com/adamkiss)",
        "Fernando Barrosl (https://github.com/)",
        "James Stout (https://github.com/jamesstout)",
        "Jamie Mason (https://github.com/JamieMason)",
        "Jason Grantl (https://github.com/oo12)",
        "Martin Schürrer (https://github.com/MSch)",
        "Ramiro Araujol (https://github.com/ramiroaraujo)",
        "Simen Brekken (https://github.com/sbrekken)",
        "Stefan Crain (https://github.com/stefancrain)",
        "Tom Chenl (https://github.com/tomchentw)"
    ],
    "devDependencies": {
        "grunt": "1.0.1",
        "grunt-cli": "1.2.0",
        "grunt-contrib-concat": "1.0.1",
        "grunt-contrib-watch": "1.0.0"
    },
    "homepage": "https://github.com/JamieMason/ImageOptim-CLI",
    "keywords": [
        "advpng",
        "compress",
        "compress images",
        "gifsicle",
        "image compression",
        "image optimisation",
        "imagealpha",
        "imagemin",
        "imageoptim",
        "images",
        "jpegmini",
        "jpegoptim",
        "jpegtran",
        "optimise images",
        "optipng",
        "pngcrush",
        "pngout",
        "pngquant",
        "smushit",
        "tinypng"
    ],
    "license": "MIT",
    "main": "./bin/imageOptim",
    "repository": {
        "type": "git",
        "url": "git://github.com/JamieMason/ImageOptim-CLI.git"
    },
    "scripts": {
        "build": "grunt build",
        "watch": "grunt watch"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
