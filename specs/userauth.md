Feature: User Login

User enters:
- email
- password

Backend API:
POST /api/login

Request:
{
  "email": "string",
  "password": "string"
}

Response:
{
  "token": "string"
}
