# Build an e-commerce app with NestJS

**Documentation:**

NestJS is one of the best Node frameworks for building server-side 
applications. we’ll explore how to build a simple NestJS ecommerce app, 
demonstrating many of Nest’s major features along the way.

We’ll cover:

• Getting started with our NestJS ecommerce app
• Creating the NestJS ecommerce store product feature
• Creating the user management feature
• Creating user authentication and authorization
• Creating the store cart feature for our NestJS ecommerce app

Getting started with our NestJS ecommerce app:

Modules:
Definition: Modules are used to organize and structure a Nest.js application. 
At least one root module is required to create an app.

Composition: Modules can contain controllers, services, and even other 
modules.

Dependency Injection: Nest uses the dependency injection pattern to 
connect modules with their dependencies.

Controllers:

Responsibility: Controllers handle incoming HTTP requests, validate 
parameters, and return responses to the client.

Clean and Simple: Controllers should be kept clean and simple, with most of 
the complex logic delegated to services.

Services:

Role: Services hold the business logic and application functionality. Complex 
logic should be implemented within services.
Provider: Services are a type of class known as providers.
Dependency Injection: Services can be injected into controllers or other 
services.

Providers:

Definition: Providers are classes that can be injected as dependencies.
Types: Besides services, providers can include classes like repositories, 
factories, helpers, etc
