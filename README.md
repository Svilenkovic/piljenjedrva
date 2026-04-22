# Piljenjedrva

Produkcioni sajt za usluge secenja/piljenja drva sa javnom prezentacijom usluga i kontakt mehanizmom.

## Tehnologije

- PHP
- HTML/CSS/JavaScript
- Composer (`composer.json`)

## Bitni fajlovi

- `index.php`: glavna stranica
- `send_email.php`: slanje upita sa sajta
- `style.css`, `script.js`: vizuelni i interaktivni sloj
- `robots.txt`, `sitemap.xml`: SEO osnove

## Lokalno pokretanje

```bash
composer install
php -S 127.0.0.1:8080
```

## Live Preview

- https://piljenjedrva.svilenkovic.com

## Odrzavanje i bezbednost

- Nikad ne komituj tajne kredencijale za SMTP/API.
- Testiraj `send_email.php` u staging okruzenju pre produkcionog deploy-a.
- Redovno proveravaj anti-spam i validaciju inputa u formama.
