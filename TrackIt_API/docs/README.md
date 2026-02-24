# Trackit API Documentation

This project showcases a fictional REST API specification and its corresponding human-readable API reference documentation. The goal of this project is to demonstrate practical experience in designing and documenting APIs using OpenAPI (Swagger) and structured reference documentation.

<br>

## 📌 Project Overview

**Trackit** is a fictional task management API designed for personal productivity use cases. 

It includes endpoints for:

- Authentication (register / login)
- User profile management
- Projects management
- Tasks management
- Notifications

This API is not connected to a live backend. It was intentionally created as a specification-first documentation project.

<br>

## 📂 Repository Structure

```
/docs
 ├─ api/
 │  ├─ openapi.yaml        # OpenAPI 3.0 specification
 │  └─ api-reference.md    # Human-readable API reference
 └─ README.md              # Project overview
```

- `openapi.yaml`: Defines endpoints, request/response schemas, and enums.
- `api-reference.md`: Structured developer-facing documentation derived from the OpenAPI specification.

<br>

## 🎯 Purpose of This Project

This project demonstrates:

- Ability to write a complete OpenAPI 3.0 specification
- Consistent schema and enum modeling
- Clear and structured API reference documentation
- Professional developer portal style formatting
- Separation of specification and documentation layers

<br>

## 🛠 Documentation Approach

This project follows a **spec-first documentation workflow**:

1. Define the API contract using OpenAPI.
2. Model reusable schemas and enums.
3. Generate or manually craft a structured API reference.
4. Ensure consistent response patterns (`code/message` vs `meta/data`).

<br>

## ⚠️ Disclaimer

Trackit API is fictional and created solely for documentation portfolio purposes.

<br>

