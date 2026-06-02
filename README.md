# Kritikal

Kritikal is a browser panel script with feature tabs, visual effects, mini games, feature search, and an AI helper tab.

## Files

- `kritikal.js` - main script for console use
- `kritikal-bookmarklet.js` - bookmarklet URL payload
- `kritikal-features.txt` - full feature list

## Run in Console

1. Open the target page.
2. Open DevTools (`F12` or `Ctrl+Shift+I`).
3. Open the **Console** tab.
4. Copy everything from `kritikal.txt`.
5. Paste and press Enter.
6. Toggle panel visibility with `Ctrl+E`.

## Run as Bookmarklet

1. Open `kritikal-obfuscated-bookmarklet.txt`.
2. Copy the full single line that starts with `javascript:`.
3. Create a bookmark in your browser.
4. Paste that line into the bookmark URL field.
5. Open the target page and click the bookmark.

## Basic Use

- Left sidebar switches sections
- Top controls handle fullscreen, feature search, minimize, and close
- **Terminal** has the mini games
- **AI Assistant** is for prompt help tied to Kritikal UI/features
- **Settings** includes themes, effects, keybinds, and import/export options

## AI Assistant Setup

Some pages block direct API calls because of CSP. If that happens:

1. Open **AI Assistant**
2. Select a provider
3. Enter API key
4. Set **AI Proxy URL** if direct calls are blocked
5. Save settings and send your prompt

Current providers include OpenAI, OpenRouter, Groq, Anthropic, Google, Together, Mistral, DeepSeek, xAI, Fireworks, Cohere, Perplexity, Moonshot, Novita, SambaNova, NVIDIA, and Cerebras.

## Common Problems

- **Script does not open**: confirm the full script was pasted and no console syntax error appeared
- **AI request fails**: use the proxy field in AI Assistant
- **Background image fails**: use a CSP-allowed host or import a local image
- **Bookmarklet does not run**: make sure the URL is one continuous `javascript:` line

## Notes

- Keep API keys private
- Do not paste unknown scripts
- Review code before sharing builds
