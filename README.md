# imba-node-watch
This tiny CLI tool watches for changes in `*.imba` files and restarts the given imba file as node application. It is needed when you develop server-side application in Imba.
Uses [chokidar](https://github.com/paulmillr/chokidar) under the hood.

Doesn't create compiled js-files -> no mess with temporary output js-files.

1. Install package as develop dependency: `yarn add imba-node-watch -D`
2. Add script for monitoring in your package.json: `"dev": "imbaw source/index.imba"`. **imbaw** is a cli program to monitor and restart imba app and it takes only one parameter - the filename to run.
3. Start your application: `yarn dev`

I use yarn, but the same would work with npm.
