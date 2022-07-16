# The BFF Pattern (Backend for Frontend)

## [The BFF Pattern (Backend for Frontend): An Introduction](https://blog.bitsrc.io/bff-pattern-backend-for-frontend-an-introduction-e4fa965128bf "Viduni Wickramarachchi (Medium)")

In a situation like this, we can use a BFF in order to shift some of this front-end logic to an intermediate layer.
The intermediate layer is the BFF. When a frontend requests some data, it will call an API in the BFF.

## [Building a Backend for Frontend (BFF) For Your Microservice](https://nordicapis.com/building-a-backend-for-frontend-shim-for-your-microservices/ "Kristopher Sandoval")

A Backend for Frontend is a unique type of shim that fills a design gap that is inherent in the API process. A BFF is, in simple terms, a layer between the user experience and the resources it calls on. When a mobile user requests data, in a BFF situation, their request is translated through the BFF and into a general layer below it.

### Discussions

- [The Backends for Frontend](https://www.reddit.com/r/programming/comments/lnxym4/the_backends_for_frontends_bff_pattern/)

- [Should you adapt your backend for the frontend or the opposite?](https://www.reddit.com/r/learnprogramming/comments/mt5dhi/should_you_adapt_your_backend_for_the_frontend_or/)

### Summary

In a Microservice Architecture
Front End makes API calls to multiple Services

BFF Pattern will provide a Facade - a layer between the Front End and the Microservice

Look up GraphQL for The BFF Pattern
[GraphQL is my preferred way to do BFFs](https://christianlydemann.com/the-complete-guide-to-backend-for-frontend-bff/)

[GraphQL Mental Model](https://blog.logrocket.com/simplifying-the-graphql-data-model/)
