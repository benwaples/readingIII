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


## [using express middleware]()


## [express middleware]()


## [express middleware list]()