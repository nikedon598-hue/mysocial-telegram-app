# MySocial — Telegram Mini App

A mobile-first Facebook-style social feed starter built with React + Vite.

## Run locally

1. Install Node.js 18+.
2. In this folder run:
   npm install
   npm run dev
3. Open the local Vite URL.

## Telegram setup

This UI already loads Telegram's WebApp SDK and calls `ready()` / `expand()` when available.

For production:
1. Create a Telegram bot with @BotFather.
2. Host the built app on HTTPS.
3. Configure the bot's Mini App / menu button URL in BotFather.
4. Add a backend that validates Telegram `initData` before trusting the user identity.
5. Replace demo posts with API/database calls.

## Current demo features

- Responsive social feed
- Stories row
- Create text post
- Like/unlike
- Comments modal
- Search
- Notifications
- Friends
- Profile
- Telegram user information when opened inside Telegram

This starter intentionally uses demo data and public image URLs; it is not yet a production social network backend.
