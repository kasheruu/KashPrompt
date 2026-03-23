# KashPrompt (Image -> Prompt)

This repo is a simple static front-end app (`index.html`, `script.js`, `style.css`) that reverse-engineers an uploaded image into a detailed prompt using the Google Gemini API.

## Run locally

1. Open `index.html` in your browser, **or** use a dev server (recommended).
2. For VS Code / Cursor, install the recommended **Live Server** extension and click “Go Live”.

## Gemini API key

Your API key is stored only in your browser via `localStorage` (you enter it in the UI). Avoid using a key that has access to sensitive projects.

## Notes / limitations

- This is a purely client-side app: the API request happens from the browser.
- If Gemini responds with an unexpected structure, the UI will show an error message.

