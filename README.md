flow-remove-types
=================

This is a fork of [flow-remove-types v1](https://github.com/facebookarchive/flow-remove-types), an older version of Facebook's [Flow types](https://flow.org/) removal tool that's based on the [Babel parser](https://babeljs.io/docs/en/babel-parser).

The current official version of the tool is based on [Flow parser](https://github.com/facebook/flow/tree/master/packages/flow-parser), which is compiled to JavaScript from OCaml and its performance is unsuitable for our projects — about 4–5 times slower than this fork. We're maintaining the fork to keep our testing and bundling pipelines in [Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js) fast.

Published on NPM under [@mapbox/flow-remove-types](https://www.npmjs.com/package/@mapbox/flow-remove-types).
