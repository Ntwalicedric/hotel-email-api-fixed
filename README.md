# Ivy Resort Email API

This is the email API service for Ivy Resort booking confirmations.

## Environment Variables

- `GMAIL_USER`: Gmail address for sending emails
- `GMAIL_PASS`: Gmail app password
- `PORT`: Server port (default: 3001)

## Endpoints

- `POST /api/send-email`: Send booking confirmation email
- `GET /api/health`: Health check
- `GET /`: API information

## Deployment

This API is designed to be deployed on Render, Railway, or similar platforms.
