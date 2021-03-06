# Internet Archive Google Action [![Build Status](https://travis-ci.org/internetarchive/internet-archive-google-action.svg?branch=master)](https://travis-ci.org/internetarchive/internet-archive-google-action) [![Coverage Status](https://coveralls.io/repos/github/internetarchive/internet-archive-google-action/badge.svg?branch=master)](https://coveralls.io/github/internetarchive/internet-archive-google-action?branch=master)

## Run Local

Run server local with colorful logs

```
DEBUG=ia:* npm start
```

## How to make contributions?

:mag: get [one good first issue](https://github.com/internetarchive/internet-archive-google-action/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
assign yourself (if you have assess) or write comment that you'd like to work on this issue.
That's help to prevent work overlapping.

_create git branch `feature/<name-of-feature>`, [more](http://nvie.com/posts/a-successful-git-branching-model/)_

:computer: working on it

_Use [Mocha](https://mochajs.org/) for continuous checking of
your code quality and cover functionality by tests_

```
npm run mocha -- --watch
```

:coffee: Complete checking of code by run unit tests and code style checking

```
npm test
```

:star2: We follow [standard javascript code style](https://standardjs.com/).

_Automatic style fixing, it doesn't solve all problems but could be very helpful_

```
npm run lint -- --fix
```

:tada: Finally make Pull Request and give complete description what have you done
and link the addressed issue.

_Also it could be good practice to create your Pull Request earlier,
but add `WIP: ` at the beginning of its name! This way other developers
could see what are you working right now._
