# dotnet

learning dotnet framework

---

## Dotnet framework basics

- Kestrel is the default web server which constructs a `HttpContext` object that can be procesed by our application.
- The response is raw http
- C# compiler Roslyn is open source as is C#
- Can also package .NET runtime with the app in Self Contained Deployment (SCD) and target some specific platform like Linux.

---

## REST Constraints - Representational state transfer

- Client server approach
- Statelessness
- Cacheability
- Layered Approach
- Code On Demand (COD) - optional and poses security risk
- Uniform Interface
  - Identification of resources
  - Self Descriptive Messages
  - Manipulation of Resources through representations
  - HATEOAS - Hypermedia As the engine of application state

  REST was described by Roy Fieldings in 2000AD in his dissertation.

## SOAP - Simple Object Access Protocol

Useless in this day and age.

## GraphQL

- Reduces redundant calls and overfetching and the complexity of API endpoints compared to REST.
- Uses same data format (JSON) and protocol (HTTP) as REST.
- We send a SQL like query and get a response back from the server with requested fields satisfying constraints.

---

## 
