# imba-node-watch
I've used **nodemon** for restarting a node app on files change. But it is not tiny, so I decided to write my own. Here is a small cli (a lightweight wrapper around **gaze**) for comfortable node application developing (using Imba).

1. Install package as develop dependency: `yarn add imba-node-watch -D`
2. Add script for monitoring in your package.json: `"dev": "imbaw source/index.imba"`. **imbaw** is a cli program to monitor and restart imba app and it takes only one parameter - the filename to run.
3. Start your application: `yarn dev`

I use yarn, but the same would work with npm.
