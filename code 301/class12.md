# Reading

- In your own words, describe what each group of status code represents:

- 100’s = These are informational status codes,  the request has been received and the server will try to comply with a transmission demand of the client
- 200’s = These are the success codes,this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.


- 300’s = These are redirection codes,  the resource isn’t available at the expected location anymore.
- 400’s = These are the client error codes, A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.


- 500’s = These are the server error codes, Often they indicate problems with overwhelmed servers or unreachable servers behind proxies.

1. What is a status code 202?
- Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future.
2. What is a status code 308?
- Permanent Redirect - This is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future. The current endpoint can’t control the clients’ behavior after the request and a subsequent redirect if the resource URL changes again have to be issued from the new URL.

3. What code would you use if an update didn’t return data to a client?
- 204 No Content
4. What code would you use if a resource used to exist but no longer does?
- 410 Gone
5. What is the ‘Forbidden’ status code?
- 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource

# Videos

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
- to secure the website
2. What is middleware?
-  software that provides common services and capabilities to applications outside of what's offered by the operating system.

3. What does app.use(express.json()) do?
- It parses incoming JSON requests and puts the parsed data in req.

4. What does the /:id mean in a route?
- The path that gets you to this function.


5. What is the difference between PUT and PATCH?
- PUT is a method of modifying resource where the client sends data that updates the entire resource . PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

6. How do you make a default value in a schema?
-

7. What does a 500 error status code mean?
- the server encountered an unexpected condition that prevented it from fulfilling the request.

8. What is the difference between a status 200 and a status 201?
- The 200 status code means that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created
