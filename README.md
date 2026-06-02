# Kritikal

Kritikal is a browser panel script for gameplay tooling, UI utilities, effects, feature search, and an AI helper tab.

## Files

- `kritikal.txt` — main console-ready script.
- `kritikal-obfuscated.txt` — obfuscated script version.
- `kritikal-obfuscated-bookmarklet.txt` — encoded `javascript:` bookmarklet payload.
- `kritikal-features.txt` — full feature reference.

## Quick Start (Console Version)

1. Open the target site in your browser.
2. Open Developer Tools (`F12` or `Ctrl+Shift+I`).
3. Go to the **Console** tab.
4. Open `kritikal.txt`, copy all content, and paste it into the console.
5. Press Enter to run.
6. Use `Ctrl+E` to show/hide the panel.

## Bookmarklet Version

1. Open `kritikal-obfuscated-bookmarklet.txt`.
2. Copy the entire single line (starts with `javascript:`).
3. Create a new browser bookmark.
4. Set the bookmark URL to the copied line.
5. Open the target page.
6. Click the bookmark to inject and launch Kritikal.

## Using the Panel

- Use the left sidebar to switch sections.
- Use the top controls for fullscreen, feature search, minimize, and close.
- Use **Terminal** for arcade mini-games.
- Use **AI Assistant** for prompt-based help tied to Kritikal features.
- Use **Settings** to import/export themes, change keybinds, and configure visuals.

## AI Assistant Setup

Some environments block direct API calls through Content Security Policy (CSP). If direct requests fail:

1. Open the **AI Assistant** tab.
2. Choose provider.
3. Enter your API key.
4. Fill in **AI Proxy URL** if direct requests are blocked.
5. Save settings and send prompts.

Supported providers include OpenAI, OpenRouter, Groq, Anthropic, Google, Together, Mistral, DeepSeek, xAI, Fireworks, Cohere, Perplexity, Moonshot, Novita, SambaNova, NVIDIA, and Cerebras.

## Common Issues

- **Nothing happens after run**: verify paste completed and no console syntax errors.
- **API calls blocked**: use the AI proxy field in AI Assistant.
- **Image URL blocked**: use a CSP-allowed host or use local image import.
- **Bookmarklet not running**: ensure the URL starts with `javascript:` and is a single uninterrupted line.

## Safety Notes

- Keep API keys private.
- Do not paste unknown scripts into console.
- Review script behavior before sharing or deploying.
