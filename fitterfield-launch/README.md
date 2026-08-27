# FitterField V1 — Customer-Ready Launch Scaffold

This package is the production-oriented scaffold for FitterField V1.

## Product structure
- Apprentice
- Journeyman
- Foreman
- Helper intentionally removed

## Included
- Existing FitterField V1 landing/app UI
- Account registration and login
- Secure bcrypt password hashing
- HTTP-only session authentication
- PostgreSQL users, sessions and cloud-saved app data
- Stripe Checkout for the $29.99 one-time Pro purchase
- Stripe checkout webhook support
- Render deployment configuration

## Required production environment variables
- `DATABASE_URL`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `APP_URL`

Never commit Stripe secret keys or database passwords to the repository.
