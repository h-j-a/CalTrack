# CalTrack 🍜

An AI-powered calorie tracking web app. Scan food with your camera, track macros, and get personalized meal suggestions — all from your browser.

**[Try it live →](https://heroic-puffpuff-aac990.netlify.app)**

---

## Features

- 📷 **AI Food Scanning** — Take a photo of your meal and get instant calorie and macro estimates
- 🧊 **Fridge Analyzer** — Scan your fridge and get meal ideas based on what you have
- 📊 **Macro Tracking** — Track protein, carbs, and fat with a visual ring chart
- 💡 **Meal Suggestions** — Get AI-powered meal ideas based on your remaining calories
- ⚖️ **Weight Log** — Track your weight over time
- 🔥 **Streak Tracker** — Stay motivated with a daily logging streak
- 📅 **History** — Browse your meal history day by day
- 📦 **Barcode Scanner** — Scan packaged food barcodes for nutrition info

---

## Getting Started

CalTrack runs entirely in your browser — no install needed. Just open the link and add your own free Gemini API key in Settings.

### How to get a free Gemini API key

1. Go to [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Sign in with a Google account
3. Click **"Create API key"** → **"Create API key in new project"**
4. Copy the key
5. Open CalTrack → go to **Settings** → paste your key and save
6. You'll also need to set up billing on your Google account to activate the free tier — you won't be charged for normal usage. Go to [aistudio.google.com/projects](https://aistudio.google.com/projects) and click **"Set up billing"** next to your project.

> **Note:** The free tier includes 10 requests per minute which is more than enough for personal use.

---

## Tech Stack

- HTML, CSS, JavaScript — single file app, no frameworks
- [Google Gemini API](https://ai.google.dev) — AI food analysis and meal suggestions
- [USDA FoodData Central](https://fdc.nal.usda.gov) — Nutrition database for barcode scanning
- localStorage — all data stored locally in your browser
- Deployed on [Netlify](https://netlify.com)

---

## Running Locally

No build steps needed. Just download `CalTrack.html` and open it in Safari or Chrome.

```
1. Download CalTrack.html
2. Open in Safari or Chrome
3. Add your Gemini API key in Settings
```

> Camera and API features require Safari or Chrome. Does not work in the Claude.ai preview.

---

## Privacy

All your meal data, goals, and logs are stored **locally in your browser** using localStorage. Nothing is sent to any server except the food photos/descriptions you send to the Gemini API for analysis. Your API key is stored only in your browser and never leaves your device.

---

## Screenshots

*Coming soon*

---

## License

MIT — free to use and modify.
