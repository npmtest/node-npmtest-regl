# npmtest-regl

#### basic test coverage for  [regl (v1.3.0)](https://mikolalysenko.github.io/regl)  [![npm package](https://img.shields.io/npm/v/npmtest-regl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-regl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-regl.svg)](https://travis-ci.org/npmtest/node-npmtest-regl)

#### regl is a fast functional WebGL framework.

[![NPM](https://nodei.co/npm/regl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/regl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-regl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-regl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-regl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-regl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-regl/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-regl/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-regl/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-regl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-regl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-regl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-regl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-regl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-regl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-regl/build/test-report.html](https://npmtest.github.io/node-npmtest-regl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-regl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-regl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-regl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-regl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-regl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-regl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-regl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-regl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikola Lysenko"
    },
    "browserify": {
        "transform": "./browserify/transform"
    },
    "bugs": {
        "url": "https://github.com/mikolalysenko/regl/issues"
    },
    "dependencies": {},
    "description": "regl is a fast functional WebGL framework.",
    "devDependencies": {
        "angle-normals": "^1.0.0",
        "baboon-image": "^2.0.0",
        "bl": "^1.1.2",
        "browserify": "^13.1.1",
        "budo": "^8.1.0",
        "bunny": "^1.0.1",
        "canvas-fit": "^1.5.0",
        "canvas-orbit-camera": "^1.0.2",
        "control-panel": "^1.2.0",
        "conway-hart": "^0.1.0",
        "deglob": "^1.1.1",
        "dependency-check": "^2.6.0",
        "disc": "^1.3.2",
        "es2020": "^1.1.9",
        "falafel": "^1.2.0",
        "faucet": "0.0.1",
        "fuse-vertices": "^0.1.2",
        "geo-3d-transform-mat4": "^1.0.0",
        "getusermedia": "^1.3.7",
        "git-commits": "^1.2.0",
        "git-parse-commit": "^1.0.0",
        "gl": "^4.0.1",
        "gl-mat3": "^1.0.0",
        "gl-mat4": "^1.1.4",
        "gl-vec2": "^1.0.0",
        "gl-vec3": "^1.0.3",
        "glob": "^7.0.3",
        "google-closure-compiler": "^20160315.2.0",
        "hsv2rgb": "^1.1.0",
        "install": "^0.8.1",
        "istanbul": "^0.4.3",
        "mkdirp": "^0.5.1",
        "mouse-change": "^1.3.0",
        "mouse-position": "^2.0.1",
        "mouse-pressed": "^1.0.0",
        "mouse-wheel": "^1.2.0",
        "ncp": "^2.0.0",
        "ndarray": "^1.0.18",
        "parse-dds": "^1.2.1",
        "present": "^1.0.0",
        "primitive-sphere": "^2.0.0",
        "regl-stats-widget": "0.0.1",
        "reify": "^0.3.8",
        "remark": "^5.0.1",
        "remark-cli": "^1.0.0",
        "remark-lint": "^4.1.0",
        "remark-toc": "^3.1.0",
        "remark-validate-links": "^4.1.0",
        "resl": "^1.0.0",
        "rollup": "^0.36.1",
        "rollup-plugin-buble": "^0.14.0",
        "rollup-plugin-commonjs": "^5.0.4",
        "rollup-plugin-json": "^2.0.2",
        "rollup-plugin-node-resolve": "^2.0.0",
        "runscript": "^1.1.0",
        "seedrandom": "^2.4.2",
        "snazzy": "^3.0.0",
        "standard": "^6.0.7",
        "surface-nets": "^1.0.2",
        "tape": "^4.4.0",
        "teapot": "^1.0.0",
        "three": "^0.79.0",
        "vectorize-text": "^3.0.2",
        "vertices-bounding-box": "^1.0.0"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "ccde82eff8a8a068a559581ceacbef1afea78ebd",
        "tarball": "https://registry.npmjs.org/regl/-/regl-1.3.0.tgz"
    },
    "files": [
        "regl.js",
        "lib/*",
        "dist/*",
        "browserify/*",
        "API.md",
        "CHANGES.md",
        "package.json",
        "README.md",
        "DEVELOPING.md"
    ],
    "gitHead": "26ee1777cdc19ed48f8f752c5897cd6d83ee2122",
    "homepage": "https://mikolalysenko.github.io/regl",
    "keywords": [
        "webgl",
        "stackgl",
        "regl",
        "gl",
        "graphics",
        "computer graphics",
        "opengl",
        "glsl",
        "data",
        "flow",
        "reactive",
        "functional"
    ],
    "license": "MIT",
    "main": "dist/regl.js",
    "maintainers": [
        {
            "name": "erkaman"
        },
        {
            "name": "mikolalysenko"
        }
    ],
    "name": "regl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mikolalysenko/regl.git"
    },
    "scripts": {
        "bench-browser": "budo bench/bench.js --open",
        "bench-graph": "node bench/bench-graph.js",
        "bench-history": "node bench/bench-history",
        "bench-node": "node bench/bench-node.js",
        "build": "npm run build-script && npm run build-min && npm run build-bench && npm run build-compare",
        "build-bench": "rollup -c rollup/config.bench.js",
        "build-compare": "node bin/build-compare.js",
        "build-docs": "remark API.md -o API.md",
        "build-gallery": "node bin/build-gallery.js",
        "build-min": "rollup -c rollup/config.unchecked.js && node bin/minify.js dist/regl.unchecked.js dist/regl.min.js",
        "build-script": "rollup -c rollup/config.js",
        "cover": "istanbul cover test/util/index.js",
        "lint-docs": "remark --frail --quiet README.md API.md DEVELOPING.md CHANGES.md",
        "test": "standard | snazzy && tape test/util/index.js | faucet",
        "test-browser": "budo test/util/browser.js --open"
    },
    "standard": {
        "ignore": [
            "dist/*",
            "www/*",
            "example/util/ammo.js"
        ]
    },
    "version": "1.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
