# fuse-box-express-seed
This project is to get you started using FuseBox as module loader and bundler with `Node` and `express.js` using `TypeScript`

#### Features
`FuseBox` itself has a built in `Development Server` that is built on top of `Express.js`, but if you prefer to add `FuseBox` to existing project or wish to have more control over your server code, then this project will get you started.

the most important setting is to disable the built in `HTTP` server, so `FuseBox` will focus only on hot reloading  bundle files via `Web Sockets` and leave the rest to you.
```
fuseBox.devServer('>app.ts', {
    port: 4446,
    httpServer: false
});
```

#### Setup & run
* `npm install`
* `npm start`

Visit `http://localhost:3446/`

Don't hesitate to let us know how to improve it :)
