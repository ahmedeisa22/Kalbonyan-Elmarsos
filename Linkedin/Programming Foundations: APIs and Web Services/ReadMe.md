# APIS AND WEB SERVICES

**Web Service:**
* SOAP
* RESTFUL

**SOAP:** Simple Object Access protocal

* sends messages using XML
* XML document is sent with data

**Represnation state transfer:**
* uses a http to access resources.
  
**benefits  of web service:**
* reusability -> . This can allow organizations to use web services provided by third parties.
  
* interoperability - > his means the service provider can write the web service in one language like PHP or Node.js then the service client can be written in a totally different language, like Python, Ruby, or Perl and they can still communicate because they speak a common language, such as XML or JSON.

* usability -> more accessible to other systems in a secure fashion

* deployability -> They are deployed over standard internet technologies making them easily available on a global level. 

 **Latency** is the amount of time it takes once a request is made to receive a response.

 **A partial failure** when a server or network fails to responde.

 **Authentication**
 * validating the identity of a client
**Authorization** ->is the next step after authentication
* Determines level of client's access.

**API key authentication:** which requires the API to be accessed with a unique key.

**all web services are APIs, but not all APIs are web services.**

web services:
* dependant on soAP protocol
* which isn't a lightweight architecture

 If APIs and web services are German Shepherds, microservices could be a team of miniature German Shepherds working together. 
 ** If APIs and web services are German Shepherds, microservices could be a team of miniature German Shepherds working together.

 **When making a decision to use an API, a web service, or a microservice?**
 * ake a look at the business problem you're trying to solve,
 * the type of application you're trying to build, 
* the capabilities of your calling clients. 


---
## RESTfull APIS AND HATEOAS
**there are four principles that APIs follow:
1. Uniform Resource Identifier(URI).
2. operations
    *  GET- retrieves a resource,
   * POST- creates one,
   * PUT- to update the resource, 
   * DELETE- will remove it.
3. formats
   * HTML
   * XML
   * plain text
4. stateless
    * the server will not remember or store any state about the client that made the call

  

**payload:**
data sent between client and server

**RESTful APIS:**
* json
* XML
**SOAP based web services only allow for XML.**

**HATEOAS** stands for hypermedia as the engine of application state.

 A client interacts with a REST API entirely through the responses provided dynamically by the server. 

 ---
**SOAP overview**
It's a messaging protocol that uses XML to allow applications running on different systems or platforms to communicate

(WSDL) Web Service Description Language
all the information you need, like the data types being used in the SOAP messages, and a list of all the operations available via the web service.

**There are four parts to a SOAP message.**
* The envelope is required. It's the starting and ending tags of the message.
* The header is optional. It contains the attributes of the message
* The body is required. It contains the actual XML data that the server transmits to the receiver.
* the fault, which is optional. The fault carries information about any errors that might occur during processing the message.

---
**GraphQL:** syntax that describes how to ask for data and is generally used to load data from a server to a client. 

 GraphQL uses a type:
 *  The schema =>defines a set of types
 *  queries =>allow you to get information about specific fields from objects.
 *  resolvers => responsible for getting the data for us. 
  
  mutation, which modifies server-side data.
  subscription that allows for notification of changes to data in real time..
  
  
  ---
  ![1650065825416](https://user-images.githubusercontent.com/70604321/163652735-35449eb2-9006-4a77-962a-845d172822ca.png)
