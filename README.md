### SKILL-FORGE

## Description:
This repository contains the backend code for SkillForge, a comprehensive educational course selling platform. It provides a robust and scalable infrastructure for managing courses, users, and transactions.
The backend is built on a solid foundation of:
- MongoDB: A flexible NoSQL database that efficiently stores course data, user information, and purchase history. Its schema-less design allows for easy adaptation to evolving requirements.
- Express.js: A popular Node.js web framework that provides a streamlined and efficient way to handle HTTP requests and responses. Express's modular architecture enables customization and extensibility.
- JWT (JSON Web Tokens): A secure and standardized method for authenticating users and managing access control. JWTs are used to verify user identity and grant appropriate permissions to protected resources.
- Middleware: Reusable functions that intercept requests and responses to perform common tasks such as authentication, authorization, logging, and error handling. Middleware helps to improve code organization and maintainability.

## Features:
- User Management: Users can register, login, and update their profiles.
- Course Management: Create, edit, and manage courses with details like title, description, content, price, etc.
- Enrollment: Users can enroll in courses and access the associated content.
- Authentication and Authorization: Secure user access with JWT tokens and middleware for authorization checks.
- Admin Access: Admin login and register is also routed in the application.

