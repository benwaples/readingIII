# Summary of Reading for Class 09

## [using express routing](https://expressjs.com/en/guide/routing.html)
Routing refers to when a client makes a request to an application endpoint and the application responds with the correct data.

Methods are the verbs that are called on an express app and the methods + route specify function to execute.

```js
app.get('/dogs', () => {function})
```

* app is the express app
* get is the method
* dogs is the endpoint.
* the second argument is a call back function that is called when this endpoint it hit by a client.
<!-- what is stopping me from using a POST method to return a list from a SQL table and never actually 'posting" anything? -->

## [supertest](https://github.com/visionmedia/supertest)
superagent is a testing library in nodeJs used to test HTTP requests between clients and hosts.

The benefit of using supertest is that it can be super simple and abstract, and at the same time be very specific and granular.

you can replicate requests made in a browser by using `.send()`, `auth()`, `get()` and other methods.

basic use 
``` js
const request = require('supertest')
const expressApp = require('../lib/app.js')
// do your tests in a separate test file

describe('silly test', () => {
  it('should respond with my dogs name', await() => {
    const dog = await request.app()
      .get('/dog')
  })
})
```

## [using express middleware](https://expressjs.com/en/guide/using-middleware.html)
Express is an app of middleware function calls. It gets access to the req and res objects and ends the request-response cycle.

Express apps can use the following middleware:
* application 
* router-level 
* error-handling
* built-in
* third-party


## [express middleware](https://www.tutorialspoint.com/expressjs/expressjs_middleware.htm)
there are loads of different middleware to be used in an express app. Each does a different task, such as body-parser that gets the body off of a request


## [express middleware list](https://expressjs.com/en/resources/middleware.html)
go here to see all the middleware you can use with an express app. 