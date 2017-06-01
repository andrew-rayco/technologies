# technologies
Getting a grip on all the tech and concepts that I'm fuzzy on

## React-router
To write routes in React I guess.
Doesn't always seem necessary for routes? Why not?

## Superagent
It is an API, or accesses API?
Example: 
```javascript
request
  .post('/api/pet')
  .send({ name: 'Manny', species: 'cat' })
  .set('X-API-Key', 'foobar')
  .set('Accept', 'application/json')
  .end(function(err, res){
    // Calling the end function will send the request 
  });
```
  
## Promises
https://www.promisejs.org/
The core idea behind promises is that a promise represents the result of an asynchronous operation. A promise is in one of three different states:

pending - The initial state of a promise.
fulfilled - The state of a promise representing a successful operation.
rejected - The state of a promise representing a failed operation.
Once a promise is fulfilled or rejected, it is immutable (i.e. it can never change again).
