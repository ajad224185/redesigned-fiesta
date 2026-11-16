# Redesigned Fiesta / SSC PrepX Learning App

Firebase Realtime Database learning portal with admin panel.

## Firebase
```
https://dora-dora-2e0e6-default-rtdb.asia-southeast1.firebasedatabase.app
```

## Shareable batch links
```
https://YOUR-DOMAIN/?batch=-P19ln1wMk0Y8ihkvdeG
```
Opens PARMAR GK 5.0 (or any course key) directly after unlock.

## Iframe embedding
`vercel.json` sets `Content-Security-Policy: frame-ancestors *` so this app can open **inside** your main website iframe.

## Deploy
1. Push to GitHub
2. Import on Vercel (Framework: Other)
3. Deploy

## Files
- index.html — main app
- firebase-*.js — local Firebase SDK copies
- vercel.json — iframe allow headers
