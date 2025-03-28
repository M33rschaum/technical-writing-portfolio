# 📘 Idea Center – API Documentation

This documentation outlines the main endpoints of the **Idea Center REST API**, designed to manage users and ideas. The API follows the OpenAPI 3.0 (Swagger) specification.

---

## 🔗 Base URL

```
http://softuni-qa-loadbalancer-2137572849.eu-north-1.elb.amazonaws.com:84/api
```

> 🔍 **Swagger UI:**  
> http://softuni-qa-loadbalancer-2137572849.eu-north-1.elb.amazonaws.com:84/swagger/index.html

> 📋 **List of all supported methods:**  
> http://softuni-qa-loadbalancer-2137572849.eu-north-1.elb.amazonaws.com:84/api/Info/Methods

---

## 🔐 Authentication

To access the **IdeaCenter** endpoints, you must first authenticate and retrieve a bearer token.

### `POST /api/User/Authentication`

Authenticate an existing user.

#### Request Body

```json
{
  "email": "user@example.com",
  "password": "string"
}
```

#### Response Example

```json
{
  "accessToken": "eyJhbGciOiJ..."
}
```

🛡️ **Important:** Add this token under `Authorization → Bearer Token` in all future requests.

---

## 👤 User Endpoints

### `POST /api/User/Create`

Create a new user.

#### Request Body

```json
{
  "userName": "string",
  "email": "user@example.com",
  "password": "string",
  "rePassword": "string",
  "acceptedAgreement": true
}
```

---

## 💡 Idea Endpoints

> 🧾 **Note:** All of the following endpoints require a valid bearer token.

### `GET /api/Idea/All`

Retrieve all submitted ideas.  
🟢 No request body required.

---

### `POST /api/Idea/Create`

Submit a new idea.

#### Request Body

```json
{
  "title": "string",
  "url": "",
  "description": "string"
}
```

---

### `PUT /api/Idea/Edit?ideaId={id}`

Edit an existing idea by ID.

#### Query Parameter

```
?ideaId=123
```

#### Request Body

```json
{
  "title": "string",
  "url": "http://example.com",
  "description": "string"
}
```

---

### `DELETE /api/Idea/Delete?ideaId={id}`

Delete an existing idea.

#### Query Parameter

```
?ideaId=123
```

---

## 📚 Data Models

### `UserModel`

```json
{
  "email": "string",
  "password": "string"
}
```

---

### `RegisterModel`

```json
{
  "userName": "string",
  "email": "user@example.com",
  "password": "string",
  "rePassword": "string",
  "acceptedAgreement": true
}
```

---

### `IdeaCreateModel`

```json
{
  "title": "string",
  "url": "string",
  "description": "string"
}
```

---

## 🛠️ Notes

- Use **Postman**, **curl**, or Swagger UI to test endpoints
- API returns HTTP 200 on success
- Authentication is required for all `/api/Idea/*` endpoints
- The system does not implement pagination or filtering

---

📄 *This documentation is part of a technical writing portfolio project and was manually structured based on Swagger UI and testing results from the Idea Center API.*
