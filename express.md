1. What’s the difference between PUT and PATCH?
PUT: Replaces target resource with the request payload. Can be used to update or create a new resources.

PATCH: Similar to PUT, but used to update only certain fields within an existing resource.
```
Source: https://stackoverflow.com/questions/107390/whats-the-difference-between-a-post-and-a-put-http-request
```

2. Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
```
  1. https://fakestoreapi.com/
  2. https://jsonplaceholder.typicode.com/
  3. https://fakejson.com/
```

3. Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
400 for a bad request and 401 for unauthorized. 400 means the request was invalid while 401 means there was an issue with an authentication token.

4. Compare and contrast SOAP and ReST
SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State Transfer. The differences are as follows:
```
* SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State Transfer.
* SOAP is a protocol whereas REST is an architectural pattern.
* SOAP uses service interfaces to expose its functionality to client applications while REST uses Uniform Service locators to access to the components on the hardware device.
* SOAP needs more bandwidth for its usage whereas REST doesn’t need much bandwidth.
* Comparing SOAP vs REST API, SOAP only works with XML formats whereas REST work with plain text, XML, HTML and JSON.
* SOAP cannot make use of REST whereas REST can make use of SOAP.
```

# Document the following Vocabulary Terms:

Web Server - a computer software and underlying hardware that accepts requests via HTTP, the network protocol created to distribute web pages, or its secure variant HTTPS.
Express - is a back end web application framework for Node. js
Routing - Routing is the process of selecting a path for traffic in a network or between or across multiple networks.
WRRC - Web Request Response Cycle

# Preview

Skim the following materials in preparation for the upcoming lecture. Note the following as you browse the material, and be prepared to participate in discussions during lecture

Which 3 things had you heard about previously and now have better clarity on?
```
  1. Express as a framework developed for Node.js to make it simpler and more plaintext
  2. middleware
```
Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
```
  1. TDD
  2. the beginner, intermediate and advanced levels of TDD
```
What are you most excited about trying to implement or see how it works?
```
  1. TDD
  2. CI/CD, particularly making sure the dev branch passes tests and is ready to be integrated. I keep making PR's to main X_X
```