# Reading

1. What does REST stand for?
- REST stands for representational state transfer and was created by computer scientist Roy Fielding

2. REST APIs are designed around a resources.
<br>

3. What is an identifier of a resource? Give an example.
-  which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

         - https://adventure-works.com/orders/1
         
4. What are the most common HTTP verbs?
- GET, POST, PUT, PATCH, and DELETE.
5. What should the URIs be based on?
- nouns (the resource) and not verbs (the operations on the resource).
6. Give an example of a good URI.
- /customers/1/orders/99/products
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
- avoid "chatty" web APIs that expose a large number of small resources and no it is not good
8. What status code does a successful GET request return?
- 2XX
9. What status code does an unsuccessful GET request return?
-  5xx server errors
10. What status code does a successful POST request return?
- 2xx Successful
11. What status code does a successful DELETE request return?
- 200 (OK)