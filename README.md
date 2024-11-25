# Library Management System - API Documentation

## Overview

This document provides details about the RESTful API endpoints of the Library Management System, including request/response payloads and usage instructions.

---

## **Authentication**

Most endpoints require an `Authorization` header with a valid JWT token:

---

## **API Endpoints**

### **User Management**

#### 1. Login a User

- **Method:** `POST`  
- **Endpoint:** `/user/login`

**Request Body:**
```json
{
  "username": "user123",
  "password": "password123"
}
