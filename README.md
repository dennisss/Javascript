##JavaScript (+ JSX) for Light Table

The official JavaScript language plugin for Light Table.

### For Committers

* See package.json for node dependencies. Upgrade a dependency with `npm install LIB@latest --save`
* Upgrade `javascript.js` with the following where `$VERSION` is a version number tag:

    curl https://raw.githubusercontent.com/codemirror/CodeMirror/$VERSION/mode/javascript/javascript.js > codemirror/javascript.js

  `javascript.js` is currently on CodeMirror version 5.12.0.
* We rely on acorn for parsing JS. See [its readme](https://github.com/ternjs/acorn#main-parser) for
  several parsing options

###License

Copyright (C) 2013 Kodowa Inc.

Distributed under the MIT license, see LICENSE.md for the full text.
