
# Section B - API Endpoint Plan

| HTTP Method | Route | Description | Role Required | Request Body | Expected Response |
|---|---|---|---|---|---|
POST /api/auth/register
POST /api/auth/login
GET /api/users/me
PUT /api/users/me
POST/GET/PUT participant profile
POST/GET/PUT organizer profile
POST /api/events
GET /api/events
GET /api/events/{eventId}
PUT /api/events/{eventId}
DELETE /api/events/{eventId}
POST /api/events/{eventId}/categories
GET /api/events/{eventId}/categories
GET /api/categories/{categoryId}
PUT /api/categories/{categoryId}
DELETE /api/categories/{categoryId}
POST /api/categories/{categoryId}/enrollments
GET /api/enrollments/me
GET /api/enrollments/{enrollmentId}
DELETE /api/enrollments/{enrollmentId}
