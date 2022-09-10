# Readings: Express

## Review, Research, and Discussion

<br>
<br>

1. **What's the difference between PUT and PATCH?**
- PUT is a method of modifying resource where the client sends data that updates the entire resource .
- PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

2. **Provide links to 3 services or tools that allow you to "mock" an API for development like json-server**
- Postman Mock Server
- mongoDBCompass
- jest
3. **Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?**
- Swagger allows you define the range of responses as 1XX, 2XX, ...5XX. If you provide the explicit code (i.e. 404) that will take precedence over the blanket request (in this case 4XX). Each response status requires a description. API specs do not necessarily need to cover all possible codes, but known error codes like 404 must be addressed.

- APIDOC.js you can also define the errors in groups, if you do not provide the specific code the default error Error 4xx is thrown. You can set the title and description of the errror with @apiDefine
4. **Compare and contrast SOAP and ReST**
-  SOAP uses XML data in request/response messages, relying on XML Schema and other technology to enforce/parse structure of messages. It is platform indepedent (i.e. clients can use from disparate OS). SOAP is extensible, neutral, and independent of specific programming models.
- REST (Representational State Transfer) Standard software architecture for web services. This is a webservice that provides it's web services in a text form allowing them to be read and modified with a stateless protocol and predefined operations. Common, stateless protocols allow for operability amongs disparate OS.

<br>
<br>

## Document Vocabulary Terms

<br>
<br>

1. **Web Server :** is software and hardware that uses HTTP (Hypertext Transfer Protocol) and other protocols to respond to client requests made over the World Wide Web.

<br>

2. **Express :** Express is the most popular Node web framework, and is the underlying library for a number of other popular Node web frameworks.

<br>

3. **Routing :**  is how the client request is connected to the code they will receive.

<br>

4. **WRRC :** is how information flows through a web app. 

<br>


