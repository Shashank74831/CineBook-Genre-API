# CineBook | Movie Genre Management API

A backend-focused project designed to organize and serve movie genre information through RESTful API endpoints. CineBook demonstrates structured server-side development with Express.js, modular code organization, and efficient request handling.

## Overview

CineBook provides a lightweight API for accessing and managing movie genre data. It separates application logic, routing, and data storage into dedicated modules to support maintainability and future expansion.

## Core Capabilities

- **Genre Listing:** Retrieve the complete collection of available movie genres.
- **Genre Lookup:** Access individual genre records using their identifiers.
- **Genre Creation:** Add new genre entries through HTTP POST requests.
- **Modular Backend:** Separate controllers, routes, and data modules.
- **JSON Responses:** Deliver structured responses for API consumers.

## Technology Stack

| Technology | Purpose |
|---|---|
| Node.js | Server-side JavaScript runtime |
| Express.js | Backend framework |
| JavaScript | Application logic |
| REST Architecture | API communication |
| JSON | Data exchange format |

## Architecture

```text
CineBook/
│
├── controller/
│   └── cinecontroller.js
│
├── data/
│   └── store.js
│
├── routes/
│   └── cineRoutes.js
│
├── screenshots/
│   ├── 01-home.png
│   ├── 02-all-genres.png
│   └── 03-genre-by-id.png
│
├── app.js
├── server.js
├── package.json
├── package-lock.json
└── .gitignore
```

## Getting Started

**Prerequisites:** Node.js and npm.

Clone the repository:

```bash
git clone https://github.com/Shashank74831/CineBook-Genre-API.git
```

Enter the project directory:

```bash
cd CineBook-Genre-API
```

Install required packages:

```bash
npm install
```

Launch the application:

```bash
node server.js
```

The server will start on the configured port.

## API Reference

| HTTP Method | Endpoint | Function |
|---|---|---|
| GET | `/` | API status |
| GET | `/api/genres` | Fetch all genres |
| GET | `/api/genres/:id` | Fetch a specific genre |
| POST | `/api/genres` | Create a genre |

## Development Focus

This project demonstrates practical implementation of:

- RESTful service design
- Express routing and middleware
- Controller-based request handling
- Data organization and retrieval
- Backend project structuring

## Future Scope

- Database integration
- Search and filtering capabilities
- Input validation and error handling
- Authentication and authorization
- Integration with a movie discovery frontend

## Developer

**Shashank74831**

[GitHub Profile](https://github.com/Shashank74831)

---

*Built as a backend development project to explore API design and server-side application architecture.*
