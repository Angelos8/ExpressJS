# ExpressJS
This repository contains documentation on how to use Express JS. 

## Installation
To install run **npm install *express --save***

## Create a basic Express server
Once the Express package is installed, create a file server.js and write the following code to start the express server:

```server.js
const express = require('express')
const app = express()
const port = 3000

app.get('/', (request, response) => {
  response.send('Hello World');
})

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`)
})
```
On the terminal run **node server.js** and open *localhost:3000* on your browser to see the home route.

