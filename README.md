# node-traceur

### DEPRECATED

Please use the official [traceur](https://www.npmjs.org/package/traceur) package and refer to this [github repo](https://github.com/google/traceur-compiler)

* * *

This is a mirror of the traceur compiler hosted on code.google.

For more information about Traceur Compiler, visit:
http://code.google.com/p/node-traceur/

It was slightly adapted to include only the files necessary to consume it from another node.js module and make that easier.

Please find the original readme [here](https://github.com/thlorenz/node-traceur/blob/master/GOOGLE_README).

## Installation

~~npm install node-traceur~~

Use official traceur instead: 

      npm install traceur

## API

As part of the adaptation the entire API is exposed properly so things like
`require('traceur/src/node/compiler')` are no longer necessary.

Please consult the [index file](https://github.com/thlorenz/node-traceur/blob/master/index.js) to see what is exposed from where.

**Note:** I welcome additions from anyone (especially the Chromium authors) that add more API documentation here.

## TODO

Use [source-map](https://npmjs.org/package/source-map) npm module instead of including it in [third_party](https://github.com/thlorenz/node-traceur/tree/master/third_party)

That however requires fixing all references to it in the code and at this point I didn't want to take that on.
