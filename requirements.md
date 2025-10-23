# Airbnb Clone Backend — Requirement Specifications

## 1. User Authentication



### API Endpoints
- **POST** `/api//auth/register`: Register a new user.  
- **POST** `/api//auth/login`: Authenticate a user and issue a JWT token.  
- **GET** `/api//users/profile`: Retrieve user profile (JWT required).  

### Input/Output Specification

**Register (POST /auth/register):**
```json
Input:
{
  "first_name": "Ibrahima",
  "last_name": "Diallo",
  "email": "ibrahima@mail.com",
  "password": "SecurePass123",
  "role": "host"
}

Output:
{
  "message": "User registered successfully",
  "user_id": "uuid",
  "token": "jwt_token"
}

### Performace

-- Token generation time: < 500ms

-- Authentication endpoints handle at least 100 requests/second.


