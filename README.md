# API Tests – Postman

This repository contains REST API tests written in Postman.

The tests cover CRUD operations for Posts and Comments
using a local mock REST API powered by json-server.

## Tech stack
- Postman
- REST API
- json-server

## Mock API
The mock API is provided by json-server and must be running locally.

Start the server:
```bash
json-server --watch mock-api/db.json --port 3000
