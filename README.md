***```express-replit.js```***

[About](#About)
[Installation](#Installation)
[Credits](#Credits)

## About
express-replit is a module that with help you to get your [Repl](https://bit.ly/replithome) always on when used with a pinger (like: uptime_robot).

## Installation

To install it you can do: 

```sh
~$ npm install express-replit@latest
```

Then import it in your file by using:

```js
const { express } = require('express-replit')
var port = 3000 // you can set the port you want ex: 5000
var ready = `Ready on port: ${port}` // you can custom this too
var text = `The server succesdfully running!` // this can be customized too

const app = new express(); // you can set any name you want intead of 'app'
app(port, ready, text); // and type the name you wanted here (replacing 'app' by the name of the const)
```

In the pinger select add a new monitor then choose ```ping```, in the url field enter your repl url and in the name field enter a name for your monitor. And set the interval time (time when the pinger go ping your repl) to 29 minutes.


Hope this help you.

## Credits

- 1st credit to: ****me****
  - discord: ****```@Star_Angel44100#0154```****
- 2nd credit to: ****my friend****
  - discord: ****```@PS MΔne 83ץ#0666```****
- 3rd credit to: ****my working team****
  - website: soon
