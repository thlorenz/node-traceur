# traceur-compiler

This is a mirror of the traceur compiler hosted on code.google.

For more information about Traceur Compiler, visit:
http://code.google.com/p/traceur-compiler/

It was slightly adapted to include only the files necessary to consume it from another node.js module and make that easier.

Please find the original readme [here](https://github.com/thlorenz/traceur-compiler/blob/master/GOOGLE_README).

## API

As part of the adaptation the entire API is exposed properly so things like
`require('traceur/src/node/compiler')` are no longer necessary.

Please consult the [index file](https://github.com/thlorenz/traceur-compiler/blob/master/index.js) to see what is exposed from where.

**Note:** I welcome additions from anyone (especially the Chromium authors) that add more API documentation here.
