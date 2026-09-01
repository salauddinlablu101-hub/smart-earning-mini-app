# Smart Earning Telegram Mini App

## GitHub structure
All files are kept in the same `smart-earning-mini-app` folder. There is **no `public` folder**.

- `server.js` — backend + Telegram bot
- `package.json` — Node.js dependencies
- `render.yaml` — Render settings
- `.env.example` — environment variable template
- `index.html` — main Mini App page + notification popup
- `app.js` — Telegram links and frontend logic
- `admin.html` — admin panel
- `style.css` — design/colors

## Easy changes later
Edit `index.html` for popup text, title and button labels.
Edit `app.js` for the two Telegram Join links:

```js
const GROUP_1_URL = "https://t.me/your_group";
const GROUP_2_URL = "https://t.me/your_channel";
```

Edit `style.css` for colors/design.

## Render environment variables
- `BOT_TOKEN`
- `BOT_USERNAME`
- `APP_URL`
- `ADMIN_PASSWORD`
