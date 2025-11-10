# Hoodik templates

Collection of Unraid templates for Hoodik

## SMTP configuration

Set these variables when `MAILER_TYPE` is `smtp`:

- **SMTP_ADDRESS**: SMTP server address (e.g., `smtp.gmail.com`)
- **SMTP_USERNAME**: SMTP account username
- **SMTP_PASSWORD**: SMTP account password (use an app password for Gmail)
- **SMTP_PORT**: SMTP port (defaults to `465` if unset)
- **SMTP_DEFAULT_FROM_NAME**: Default FROM display name (e.g., `HoodikDrive - Unraid`)
- **SMTP_DEFAULT_FROM_EMAIL**: Default FROM email (e.g., `test@gmail.com`)

Note: The previous combined `SMTP_DEFAULT_FROM` (e.g., `Your Name <user@example.com>`) has been removed because angle brackets can be parsed incorrectly in Unraid templates. Use the new split variables instead.
