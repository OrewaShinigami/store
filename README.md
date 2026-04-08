# CosmoCraft Store

A premium Minecraft server storefront and owner dashboard for Cosmo Craft.

## Features

- Space-themed public website with Home, Rules, Vote, Store, Staff, and Community pages.
- Currency switcher, cart, checkout flow, and manual payment method support.
- Password-gated owner dashboard for editing site content, store items, staff, announcements, posts, and payment methods.
- Upload support for images and videos.
- Minecraft delivery bridge API plus a Paper plugin source project for in-game rewards.

## Local setup

1. Install Node.js 20+ or 24+.
2. Copy `.env.example` to `.env.local` and update the secrets.
3. Install dependencies with `npm install`.
4. Start the app with `npm run dev`.
5. Open `http://localhost:3000`.

## Important

- The default owner password in `.env.example` matches the value requested in the brief. Rotate it before public deployment.
- Uploaded files are stored under `public/uploads`.
- Content, settings, community entries, and orders are stored as JSON files inside `data/`.

## Minecraft bridge

The Paper plugin source lives in `minecraft-plugin/`. Configure it with the same `serverId` and shared secret used by the website.
