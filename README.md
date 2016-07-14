[![Build Status](https://travis-ci.org/Gizra/elm-tlv3.svg?branch=master)](https://travis-ci.org/Gizra/elm-tlv3)

> elm-tlv3

## Steps

From a simple counter to (almost) a full [SPA example](https://github.com/Gizra/elm-spa-example), in small steps:

* [1st step; Add App component](https://github.com/Gizra/elm-tlv3/pull/1)
* [2nd step; Add navbar menu](https://github.com/Gizra/elm-tlv3/pull/2)
* [3rd step; Add Login page sub component](https://github.com/Gizra/elm-tlv3/pull/3)
* [4th step; Add user and fetch from GitHub](https://github.com/Gizra/elm-tlv3/pull/4)

## Prerequisites

Make sure the following are installed:

* NodeJs (and npm)
* Elm (e.g. `npm install -g elm@0.17.0`)
* Compass (for SASS) (`gem update --system && gem install compass`)

## Installation

```shell
npm install
elm-package install -y
```

## Usage

1. Serve locally, and watch file changes: `gulp`
1. Prepare file for publishing (e.g. minify, and rev file names): `gulp publish`
1. Deploy to GitHub's pages (`gh-pages` branch of your repository): `gulp deploy`

## Unit Tests

In order to view the tests on the browser Start elm reactor (elm-reactor) and navigate to http://0.0.0.0:8000/src/elm/TestRunner.elm

## License

MIT
