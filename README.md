# imba-node-watch
I used **nodemon** to monitor for file changes and restart the node application. But it is not tiny, so i decided to write my own. So here it is a tiny cli (a lightweight wrapper around gaze) for restarting node app after you save changes to your imba files.

1. Install package as develop dependency: `yarn add imba-node-watch -D`
2. Add script for monitoring in your package.json: `"dev": "imbaw source/index.imba"`. It takes only one parameter - the filename to run.
3. Start your application: `yarn dev`

I use yarn, but the same would work witn npm.
