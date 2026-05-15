# Security Notes

## Reporting

Report security concerns privately to the project owner. Do not publish sensitive findings in public issues.

## Public Safety Rules

- Do not commit `.env` files.
- Do not commit API keys, tokens, passwords, private keys, database URLs, SMTP credentials, payment secrets, or JWT secrets.
- Do not publish private backend, auth, admin, payment, referral, database, or production socket implementation details.
- Rotate any credential that was ever committed publicly.

## Pre-Publication Scan

Search public repos for:

```text
SECRET
TOKEN
PASSWORD
MONGODB
JWT
SMTP
STRIPE
PAYPAL
CLOUDINARY
GOOGLE
TELEGRAM
PRIVATE_KEY
API_KEY
```

