1. Name 3 real world use cases where you’d want to change the request with custom middleware
```
1. To stop a request from happening if improper data is sent; such as if it requres a JSON but doesn't get it.
Source: https://developer.okta.com/blog/2018/09/13/build-and-understand-express-middleware-through-examples
2. To change the request body somehow, such as adding a timestamp or sorting data.
3. ???
```

2. True or false: The route handler is middleware?
True

3. In what ways can a middleware function end the process and send data to the browser?
By no longer chaining with next() and instead doing a res.send(data). I'm kind of guessing on this one...

4. At what point in the request lifecycle can you “inject” middleware?
I can't find the answer to this, so I'm going to go with the request part- I'm painting with broad strokes here. The route is hit, and before the handler is called middleware is called. It can then be chained with other middleware until a response is sent.

5. What can cause express to error with “Request headers sent twice, cannot start a second response”
I can't actually find this error online, so I have to assume another error or guess. I'm guessing that if the error is the header was sent twice then it was an issue with middleware failing to chain next() appropriately and therefore failing to send a response. Another request was then generated on the frontend initiating a second response.

# Document the following Vocabulary Terms

Middleware - is a type of computer software that provides services to software applications beyond those available from the operating system.
Request Object - The object being sent to the back-end
Response Object - The object being sent to the front-end
Application Middleware - same as middleware definition above, but at the application level. My guess is focusing on the frontend and backend.
Routing Middleware - when the routing is handled as middleware.
Test Driven Development - writing code only to meet the criteria of specific tests that have been written beforehand. The tests specify what the code should be able to do.
Behavioral Testing - Behavioural Testing is a testing of the external behaviour of the program, also known as black box testing

# Preview

Which 3 things had you heard about previously and now have better clarity on?
```
1. Classes. It helps every time I look at syntax because I tend to forget things easily.
2. Routing. Once again the syntax refresher is good. I look at my code too much while writing still.
```
Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
```
1. Middleware and what it can be used for.
2. Error handling and debugging. I like fixing errors!
```
What are you most excited about trying to implement or see how it works?
```
1. I want to get a server up and running with some middleware and write some server specific tests to go with it. I hate how slow feeling TDD is, but I want to learn it and become a stronger coder.
```