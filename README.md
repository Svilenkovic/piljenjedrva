# Piljenjedrva

Public source snapshot for piljenjedrva.svilenkovic.com website.

## Sadrzaj

- Pregled
- Tehnologije
- Pokretanje lokalno
- Struktura projekta
- Live Preview
- Odrzavanje

## Tehnologije

- PHP (Composer)

## Pokretanje lokalno

```bash
composer install
# Pokretanje zavisi od okruzenja (php-fpm/nginx ili php -S)
```

## Struktura projekta

- `composer.json`
- `favicon.svg`
- `.htaccess`
- `index.html`
- `index.php`
- `index.php.bak_friends`
- `maintenance.php`
- `README.md`
- `robots.txt`
- `script.js`
- `send_email.php`
- `sitemap.xml`
- `style.css`

## Live Preview
- http://cyberpanel.net
- https://autoset.rs
- https://batastankovic.com

## Odrzavanje

- Odrzavaj README azurnim kada menjas arhitekturu, build ili deploy proces.
- Za produkcione promene vodi racuna o konfiguraciji okruzenja i bezbednosti tajnih podataka.
- Pre merge-a proveri lint/test/build korake koji postoje u ovom projektu.
