# tchat_typescript_socket-io
To run server locally, just install dependencies and run `gulp` task to create a build:

```bash
$ cd server
$ npm install -g gulp-cli
$ npm install
$ gulp build
$ npm start
```

The `socket.io` server will be running on port `8080`

When you run `npm start`, this folder leverages [nodemon](https://nodemon.io/) which will automatically reload the server after you make a change and save your Typescript file. Along with nodemon, there is also a `gulp watch` task that you can run to reload the files but it's not necessary and is provided merely as a teaching alternative. 

## Run Angular Client

Open other command line window and run following commands:

```bash
$ cd client
$ npm install
$ ng serve
```

Now open your browser in following URL: [http://localhost:4200](http://localhost:4200/)
