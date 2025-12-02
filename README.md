# claudecode

Generate a OpenAPI

```
create a open api specification 3.0 document for the below given requirements:

1. Manage user TODO's Application
    1. User Registration and Authentication
    2. Create, Read, Update, Delete (CRUD) Operations for TODO's
    3. User Profile Management
```

Create a Claude.md 

```
/init
```

Scaffloding Project

```
# 1. Backend: 
    - Built with Node.js and ExpressJS 
    - Use inmemory storage (e.g., an array or list) instead of db 
    - Define a simple "User" model with fileds: described in openapi Specification
    - Expose Rest API endpoints asper the OpenAPI Specification 

    2. Fronend: 
        -Build with React and React Router
        - create a simple UI to interact with the backend API
        - use Axios for making HTTP requests to the backend
        - use basic Bootstrap for styling the application 
    
    3. Project Structure:
        - Organize the project into separate folders for backend in "server/" and frontend in "client/" directories
        - Use a monorepo structure to manage both parts of the application in a single repository 
        - include 'package.json' files in both 'server/' and 'client/' directories to manage dependencies separately
    
    4. Add commnets to expalin each section of the code for better understanding
```

Install and Run Server and Node

```
install all dependencies and run both server and client
```

Testing your Rest API

```
# generate postman collection from openapi spec for backend api testing
```

Add Swagger for Backend

```
# for the backend application add swagger documentation
```

High Level Documentation

```
# generate below documentation in docs folder as markdown files and use mermaid diagram extension for generating diagrams for the documentation:
High Level Documentation
1. architecture overview
2. technology stack
3. module description
4. data flow diagrams
```
