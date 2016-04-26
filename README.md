[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

# Live Demo

[https://atlas7-think-in-react.herokuapp.com/](https://atlas7-react-tutorial.herokuapp.com/)

# React Tutorial - Think in React (Pete Hunt's example)

This is the React comment box example from [the React tutorial](http://facebook.github.io/react/docs/tutorial.html).

## To use

(Note: I've modified the initial NodeJS configuration to use the NodeJS `nodemon` module for server-side hot-loading. i.e server-side scripts are reloaded automatically without the need to restarting server.````)

```.sh
npm install
npm run nodemon
```

And visit <http://localhost:3000/>. Try opening multiple tabs!

## Changing the port

You can change the port number by setting the `$PORT` environment variable before invoking any of the scripts above, e.g.,

```sh
PORT=3001 nodemon --debug server.js
```

# Server-side templates for other framework

A mini NodeJS server is created. See `/server.js`.