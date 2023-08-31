# API Reference

This document outlines the endpoints and functionalities provided by the Flask API.

## Base URL

The base URL for the API is: `http://your-api-domain.com`

## Endpoints

### `GET /api/health`

Check the health status of the API.

**Request:**

```http
GET /api/health

POST /api/authenticate
Content-Type: application/json

{
  "username": "your_username",
  "password": "your_password"
}

GET /api/resource
Authorization: Bearer your_jwt_token