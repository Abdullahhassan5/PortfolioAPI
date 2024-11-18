# **Portfolio API**

This project is a **RESTful API** designed to manage project data for a portfolio application. It serves as the backend for the **Portfolio Web Application** built with Blazor.

---

## **Features**

- **CRUD operations** for project management (**Create**, **Read**, **Update**, **Delete**)
- **SQLite** database integration
- **RESTful API** endpoints
- Supports integration with frontend applications (e.g., **Blazor WebApp**)

---

## **Technologies Used**

- **C# (ASP.NET Core)**
- **Entity Framework Core** for database operations
- **SQLite** for lightweight database storage
- **Swagger** for API documentation
- **REST API** for communication

---

## **Endpoints**

### **Project Management**

| **HTTP Method** | **Endpoint**          | **Description**                 |
|------------------|-----------------------|----------------------------------|
| **GET**         | `/api/Projects`       | Fetch all projects              |
| **GET**         | `/api/Projects/{id}`  | Fetch a single project by ID    |
| **POST**        | `/api/Projects`       | Add a new project               |
| **PUT**         | `/api/Projects/{id}`  | Update an existing project      |
| **DELETE**      | `/api/Projects/{id}`  | Delete a project by ID          |

