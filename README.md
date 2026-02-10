# Flappy Trump - Border Wall Edition 🦅🧱

A Telegram Mini App game where Trump's face flaps over the US/Mexico border walls.

## Features
- Trump's cartoon face as the "bird"
- Border walls with brick texture (USA/Mexico flags)
- Desert landscape background
- Score tracking with high score saved locally
- Telegram WebApp SDK integration
- Haptic feedback on Telegram
- Share score functionality
- Responsive design

## How to Deploy as Telegram Mini App

### Step 1: Host the Game
You need to host `index.html` on a public HTTPS server. Options:

**Option A: GitHub Pages (Free)**
1. Create a new GitHub repo
2. Upload `index.html`
3. Enable GitHub Pages in repo settings
4. Your URL: `https://yourusername.github.io/repo-name/`

**Option B: Vercel (Free)**
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this folder
3. Get your deployment URL

**Option C: Netlify (Free)**
1. Drag & drop folder to netlify.com/drop
2. Get your deployment URL

### Step 2: Create Telegram Bot
1. Message @BotFather on Telegram
2. Send `/newbot` and follow prompts
3. Save the bot token

### Step 3: Set Up Mini App
1. Message @BotFather
2. Send `/mybots`
3. Select your bot
4. Click "Bot Settings" → "Menu Button"
5. Set menu button URL to your hosted game URL
6. Or use `/newapp` to create a proper Mini App

### Step 4: Configure Web App
Message @BotFather:
```
/setmenubutton
```
Then select your bot and enter your game URL.

## Local Testing
1. Open `index.html` in a browser
2. Click/tap to play
3. Space bar also works for jumping

## Game Controls
- **Tap/Click** - Make Trump flap upward
- **Space Bar** - Alternative control
- Avoid hitting the border walls!

## Customization
Edit `index.html` to change:
- Wall gap size (easier/harder): `const wallGap = 160`
- Gravity: `gravity: 0.5`
- Jump strength: `jumpStrength: -9`
- Wall speed: `const wallSpeed = 3`

## Files
- `index.html` - Complete game (single file, no dependencies)

## Tech Stack
- Vanilla JavaScript
- HTML5 Canvas
- Telegram WebApp SDK
- CSS3

---
Built by Molty 🦞
