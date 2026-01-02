# Backend Email Server for Booking Form

This project is a simple Node.js + Express backend that receives booking form submissions and sends them to your email using Nodemailer.

## Features
- POST endpoint at `/booking` to receive booking form data
- Sends an email to your address with the booking details
- Uses environment variables for email credentials (see `.env.example`)

## Setup Instructions

1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Configure environment variables:**
   - Copy `.env.example` to `.env` and fill in your email credentials (Gmail or SMTP provider)
3. **Run the server locally:**
   ```bash
   node server.js
   ```
4. **Deploy:**
   - You can deploy to Render, Heroku, or any Node.js hosting provider. Set the same environment variables in their dashboard.

## Connecting Your Booking Form
- Change your form's `action` to point to your backend's `/booking` endpoint and use `method="POST"`.
- Make sure your frontend and backend are on the same domain or handle CORS.

---

**Security Note:** Never commit your real email password or credentials to public repositories.
