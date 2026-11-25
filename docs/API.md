# KAHANI API Documentation

## Base URL
http://localhost:8000

## Health Check

### Endpoint
GET /api/health

### Response
{
  "status": "healthy",
  "version": "0.1.0",
  "message": "KAHANI API is running!"
}

## Authentication
JWT tokens in Authorization header:
Authorization: Bearer <token>

## Endpoints (Coming Soon)
- POST /auth/signup
- POST /auth/login
- GET /auth/me
- POST /api/generate
- GET /api/usage

(Full documentation to be added in Phase 1A)
