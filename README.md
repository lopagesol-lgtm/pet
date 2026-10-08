# Meadow & Paws Furniture

Single-page pet shop website. Heroku-ready.

## Open offline
Double-click `public/index.html`.

## Run locally
```
npm install
npm start
```
Open http://localhost:3000

## Deploy to Heroku
```
heroku login
heroku create meadow-paws-pet-shop
git init && git add . && git commit -m "init"
heroku git:remote -a meadow-paws-pet-shop
git push heroku main
heroku open
```

## Files
- `public/index.html` — full single-page site
- `public/hero.jpg`, `public/about.jpg` — the 2 images
- `server.js`, `package.json`, `Procfile` — Heroku stack

## Before publishing a real business
This is a fictional US-based shop concept. Replace the company name if needed, Madison location, phone placeholder, .example emails, product descriptions, and sample policies with verified business information. No checkout, contact form submission, or email service is included. Two generated illustrative photos are bundled.

Heroku uses the root package.json and Procfile. A paid Heroku dyno may be required. No build step is needed. Upload/deploy the project root, not just the public folder.
