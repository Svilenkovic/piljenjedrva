# Piljenjedrva

Production website for wood-cutting and related services, including a public service presentation and contact flow.

## Tech Stack

- PHP
- HTML/CSS/JavaScript
- Composer (`composer.json`)

## Project Structure

- `index.php`: homepage
- `send_email.php`: contact email endpoint
- `style.css`, `script.js`: styling and interactions
- `robots.txt`, `sitemap.xml`: SEO baseline files

## Local Preview

```bash
composer install
php -S 127.0.0.1:8080
```

## Live Site

- https://piljenjedrva.svilenkovic.com

## Security & Operations

- Do not commit SMTP/API credentials.
- Test `send_email.php` in staging before production deployment.
- Keep form input validation and anti-spam protections active.

## Language Note

The website content is intentionally in Serbian for the target audience.
