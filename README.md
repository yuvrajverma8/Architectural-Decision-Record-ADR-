# Architectural-Decision-Record-ADR-

# Decision Title: Choice of Technology Stack for Project X

# CONTEXT:
The Project X development team must choose the right technology stack before beginning to construct the application. This choice will have a big effect on the application's performance, scalability, maintainability, and development process.

Decision:
The following technological stack has been chosen following thorough evaluation and team discussion:

Type of Application: Hybrid Mobile Application

UI Framework: React Native

Backend Language: Node.js

Permissions: Role-based Access Control (RBAC)

Data Storage: MongoDB

Additional Frameworks/Technology Stacks: Express.js for RESTful API development, JSON Web Tokens (JWT) for authentication

# Rationale:
#1. Type of Application : Hybrid Mobile Application

- Rationale : Considering the project's significance and urgency, a hybrid strategy is selected to ensure platform compatibility while accelerating development. This choice supports the objective of timely application delivery without sacrificing user experience.

#2.UI Framework: React Native

- Rationale: React Native provides a native performance and code reusability balance that is essential for keeping projects on schedule. It is the best option for cross-platform mobile application development and maintenance due to its strong ecosystem and large community support.

#3. Backend Language: Node.js

- Rationale: A scalable and effective runtime environment for developing server-side applications is offered by Node.js. Because of its event-driven architecture, which permits non-blocking I/O operations, real-time applications can benefit from it. Using JavaScript on the front end and back end helps developers work more productively by minimising context switching.

#4. Permissions: Role-based Access Control (RBAC)

- Rationale: RBAC is a tried-and-true method that offers fine-grained control over rights by controlling access to resources according to user roles. This choice satisfies the project's security needs by enabling safe data access and preventing unauthorised operations within the system.

#5. Data Storage: MongoDB

- Rationale: The adaptable document-based data model of MongoDB is ideal for managing unstructured data, which is frequently encountered in contemporary applications. The project's scalability objectives are supported by its high availability and scalability characteristics, which provide dependable data storage and retrieval.
Extra Frameworks and Technological Stacks

#6. Additional Frameworks/Technology Stacks:
- Express.js: Express.js is a lightweight and simple framework that is ideal for developing RESTful APIs. It works well with Node.js to enable the creation of scalable backend services.

- JSON Web Tokens (JWT): JWT offers a safe and stateless authentication solution that improves the application's overall security posture without requiring sessions.
