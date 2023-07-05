app.js
//const { get } = require('http');
// create the express app
//const app=  express();
// define the port
//const port = 5000
// define the listening port
// define your route
//app.get('/', (req, res) => {
    //res.send('Hello everyone')
//})
//app.listen(port, () => {
    //console.log(`App is listening port ${port}`);
//})
 const app = express()
 const port = 5000

 app.get('/ google', (req, res) => (
    res.send("hello everyone")
 ) )

 app.listen(port, () => {
    console.log('my app is working')
 })

 Package JSON
"dependencies": {
    "ejs": "^3.1.9",
    "expres": "^0.0.5",
    "express": "^4.18.2",
    "nodemon": "^2.0.22"
  },
  "name": "africa-agility",
  "version": "1.0.0",
  "main": "app.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "nodemon app.js"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "description": ""
}
Index .ejs
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=
    , initial-scale=1.0">
    <title>Document</title>
</head>
<body>
  <h1>Africa Agility Backend Track</h1>  
</body>
</html>
