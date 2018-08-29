# Express Framework

const express = require('express'); // class
const app = express(); // Object

app.get('/', (req, res) =>{ // establish an endpoint
    res.send('Hello World');
  });


// making a get route
app.get('/api/courses', (req, res) +> {
    res.send([1,2,3]);
  });

// establish environment variable
const port = process.env.PORT || 3000;

// we are establishing an endpoint on the port
app.listen(port, () => console.log('Listening on port ${port}...'));

** Look up nodemon vs gulp, do they do the same thing? which is better?
