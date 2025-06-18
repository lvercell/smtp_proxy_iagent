
# SMTP Proxy for Hugging Face via Vercel

Este microservicio permite enviar correos vía Brevo desde Hugging Face.

## Variables necesarias (.env)
- SMTP_HOST
- SMTP_PORT
- SMTP_USER
- SMTP_PASS
- SMTP_FROM

## Endpoint
Realiza un POST a `/send` con:
- to
- subject
- html (o text)

