In your own words, describe what each group of status code represents:

100’s =Informational status codes; that usually are able tot ell the client the header part of the request has been received and the server will comply.
200’s = Successor codes, in which they tell the client that the request sent was accepted. 
300’s = Redirection code. Tells the client that the resource that they are currently requesting is not available.
400’s = Client error codes. That are about invalid requests a client sends to a server.
500’s = Server error codes. often indicate problems with overwhelmed servers.
What is a status code 202?
Often used for asynchronous processing. This code tells the client that the request was valid.
What is a status code 308?
It is for permanent redirect.
What code would you use if an update didn’t return data to a client?
401 unauthorized
What code would you use if a resource used to exist but no longer does?
404 not found
What is the ‘Forbidden’ status code?
The client has authorized or doesn't need to authorize itself, but still has no permission to access the resource.




Why do we need to pull our MongoDB database string out of our server and put it into our .env?
Because we want to create a key or value that no one can see so we put it into a separate file and to use it is by requiring that .env package in our app.js and once we require access we have authorization to that .env file containing our DB connection.
What is middleware?
A function that executes when routes are being hit.
What does app.use(express.json()) do?
It loads the package onto the file, gives you the ability to create routes.
What does the /:id mean in a route? 
It is a dynamic route and follows anything placed after it.
What is the difference between PUT and PATCH?
put is a method of modifying resources where the client sends data that updates the entire resource.
patch is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data. 
How do you make a default value in a schema?
by using a default keyword.
What does a 500 error status code mean?
internal server error
What is the difference between a status 200 and a status 201?
