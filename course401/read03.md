# Express REST API

- Name 3 real world use cases where you’d want to change the request with custom middleware
  - Checking if a user is authenticated
  - Logging data for analytics
  - Anything we'd like to do before we actually spit out information to our user.
- True or false: The route handler is middleware?
  - False, the middleware in sum cases needs next() to prevent lagging and errors
- In what ways can a middleware function end the process and send data to the browser?
  - with res.end(), the middleware executed in the live cycle of the server. and if error accrue the function middleware had res.end() it will send the data and end the process.
- At what point in the request lifecycle can you “inject” middleware?
  - between the process of request and respond. to check some cases
- What can cause express to error with “Request headers sent twice, cannot start a second response”
  - when he the respond function called more than once. So, header of response cannot been sent twice.

---

- `Middleware`: It is the process occur between the request and response  
- `Request Object`: It is a process the API do to take data or the order from the clint.
- `Response Object`: It is what the API respond or send to the clint when the clint request something from the client.
- `Routing Middleware`: It is a function in Express as a way to do something before a request is processed.
- `Test Driven Development`: It is a testing system for code to check errors and handle it.
- `Behavioral Testing`: It is a testing of the external behavior of the program, also known as black box testing. It is usually a functional testing.
