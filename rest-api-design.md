# REST API Contract

## Base URL
https://api.example.com/v1

---

## GET /users

### Description
Retrieve all users.

### Response 200

```json
[
  {
    "id": 1,
    "name": "John Doe",
    "email": "john@example.com"
  }
]
```

---

## GET /users/{id}

### Description
Retrieve user by ID.

### Response 200

```json
{
  "id": 1,
  "name": "John Doe",
  "email": "john@example.com"
}
```

---

## POST /users

### Description
Create new user.

### Response 201

User successfully created.
