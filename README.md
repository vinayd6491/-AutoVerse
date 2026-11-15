# AutoVerse — Indian Car Discovery & Comparison

AutoVerse is a PHP + MySQL college project for discovering, filtering, reviewing and comparing cars in the Indian market. It has an independent brand identity and does not integrate AI services.

## Features
- Responsive premium automotive interface
- Search cars by name, brand, body type and fuel
- Filter by budget, transmission, body type and fuel type
- Detailed car pages with specifications, features, pros and cons
- Compare 2–4 cars side by side
- INR prices (₹), variant reference prices and ex-showroom price ranges
- EMI calculator
- User registration and login
- Save/remove favourites
- Admin dashboard to add, edit and delete car listings
- SQL seed catalogue with sample Indian-market cars
- Documentation and diagrams

## Requirements
- PHP 8.1+
- MySQL 5.7+ or MariaDB 10.4+
- Apache (XAMPP recommended)
- PHP extensions: PDO MySQL, fileinfo

## Run with XAMPP
1. Extract this folder to `C:\xampp\htdocs\AutoVerse`.
2. Start Apache and MySQL in XAMPP Control Panel.
3. Open `http://localhost/phpmyadmin`.
4. Create/import database by importing `database/autoverse.sql`.
5. Check `config/database.php` (default XAMPP settings: user `root`, blank password).
6. Open `http://localhost/AutoVerse/`.

## Demo accounts
- Admin: `admin@autoverse.local` / `password`
- User: `user@autoverse.local` / `password`

Change demo passwords before any public deployment.

## GitHub upload
Upload the extracted **contents** of this folder to a repository named `AutoVerse` (not just the ZIP file).
```bash
git init
git add .
git commit -m "Initial AutoVerse release"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/AutoVerse.git
git push -u origin main
```

## Data accuracy
The included catalogue is a starter dataset for demonstration. Prices/specifications can vary by city, model year, variant and manufacturer updates. Displayed prices are marked as indicative; verify current details with manufacturers/dealers before real-world decisions. On-road price is an estimate based on a configurable percentage, not an official quote.

## Security / deployment
This is intended for local academic demonstration. Before public deployment use HTTPS, strong secrets, production-grade error handling, backups, rate limiting, server hardening and a security review. Do not use the demo credentials publicly.
