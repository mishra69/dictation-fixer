# DictFix – Voice Dictation Corrector

A web app that fixes voice dictation errors while preserving your authentic voice and style. No sign-up. Bring your own API key.

---

## How It Works

1. Select a provider (Gemini, Claude, or OpenAI)
2. Paste your API key into the key field
3. Dictate or paste your text
4. Tap **Fix It**
5. Corrected text is shown and automatically copied to your clipboard

The AI makes only surgical corrections — fixing homophones, missing punctuation, and obvious speech-to-text errors. It does **not** rephrase, change your tone, or alter your intentional style.

---

## Getting an API Key

You need an API key from whichever provider you choose. Your key is never stored — it only lives in memory for your current session.

| Provider | Model | Free Tier | Sign Up |
|---|---|---|---|
| **Google Gemini** (recommended) | gemini-2.5-flash | Yes | [aistudio.google.com](https://aistudio.google.com/app/apikey) |
| Anthropic Claude | claude-haiku | No | [console.anthropic.com](https://console.anthropic.com/) |
| OpenAI | gpt-4o-mini | No | [platform.openai.com](https://platform.openai.com/api-keys) |

Gemini 1.5 Flash is recommended because it has a free tier.

---

## Add to iPhone Home Screen

DictFix works as a full-screen app on iOS — no browser chrome, just the app.

1. Open the link in **Safari** (not Chrome or Firefox)
2. Tap the **Share** button at the bottom
3. Tap **Add to Home Screen**
4. Tap **Add**

---

## Save Your API Key with Apple Passwords

You can store your API key in Apple Passwords and fill it with Face ID or Touch ID.

**To save:**
1. Open **Settings → Passwords → +**
2. Set the website to the URL of this app
3. Set the username to your provider name (e.g. `gemini`)
4. Set the password to your API key

**To use:**
1. Tap the API key field in DictFix
2. Tap the key icon above the keyboard
3. Authenticate with Face ID or Touch ID
4. Your key is filled in automatically
