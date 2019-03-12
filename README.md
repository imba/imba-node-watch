# imba-node-watch
I used **nodemon** for a while to monitor for file changes and restart the node application. But it is not tiny, so i decided to write my own. Here is a tiny cli (a lightweight wrapper around gaze) for comfortable developing of node applications using Imba.

1. Install package as develop dependency: `yarn add imba-node-watch -D`
2. Add script for monitoring in your package.json: `"dev": "imbaw source/index.imba"`. **imbaw** is a cli program to monitor and restart imba app and it takes only one parameter - the filename to run.
3. Start your application: `yarn dev`

I use yarn, but the same would work with npm.
