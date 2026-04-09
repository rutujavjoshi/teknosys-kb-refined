# API Documentation

<span class="badge badge-advanced">Advanced</span>

---

## Overview
API documentation enables developers to understand and integrate APIs effectively.

---

## Key Components

### Endpoint
Defines the base API URL.

### Method
Supported operations:
- GET
- POST
- PUT
- DELETE

### Parameters
- Query
- Path
- Body

### Response
- Status codes
- Payload structure

---

## Example

### GET /users

**Description**  
Retrieve a list of users

**Parameters**
| Name | Type | Required | Description |
|------|------|----------|-------------|
| page | int  | No       | Pagination index |

**Response**

```json
{
  "id": 1,
  "name": "John"
}