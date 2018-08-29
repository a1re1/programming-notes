# Express Framework

## Sample Code
```JavaScript
const express = require('express'); // class
const app = express(); // Object

app.use(express.json()); //processes json

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
```

** Look up NodeMon vs gulp, do they do the same thing? which is better?
** Joi module is commonly used for input validation/error handling
when sending status message make sure to return.


## Response Codes
1xx Informational
2xx Success
3xx Redirection
4xx Client Error
5xx Server Error

### Common Response Codes
200 OK; 201 Created; 204 No Content;
304 Not Modified;
400 Bad Request; 401 Unauthorized; 403 Forbidden; 404 Not Found; 409 Conflict;
500 Internal Server Error;

### Other response codes can be found [here](https://www.restapitutorial.com/httpstatuscodes.html).
