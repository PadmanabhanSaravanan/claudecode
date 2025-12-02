# claudecode

Scaffloding Project

```
1. Backend: 
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

Create a Claude.md 

```
/init
```

Install and Run Server and Node

```
install all dependencies and run both server and client
```

Login, Logout & Role-Based JWT Auth

`use # before to use memory`

```
# Extend the existing monorepo project (server + client) by adding:
1. JWT-based authentication (login/logout)
2. In-memory users with fields: id, name, email, password, role("admin"|"user")
3. bcrypt password hashing
4. Auth endpoints:
      POST /auth/login
      POST /auth/logout
5. Middlewares:
      authMiddleware → validate JWT
      roleMiddleware → restrict routes by role
6. Protect user CRUD routes:
      GET /users → admin + user
      POST/PUT/DELETE → admin only

Frontend:
1. Add Login page using React + Axios
2. Store token in localStorage
3. Add Logout button
4. Add PrivateRoute + RoleRoute components
5. Show/hide UI based on role
6. Axios interceptor to send Authorization header

Deliver:
- Updated server and client code
- New files with comments
- Updated README with usage instructions
```

