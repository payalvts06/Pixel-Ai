# Pixel — a tiny in-browser chatbot

A simple, dependency-free rule-based chatbot built with plain HTML, CSS, and JavaScript. No build tools, no API keys, no installs — just open `index.html` in a browser.

## Run it

Just double-click `index.html`, or open it in any browser.

## How it works

- All logic lives in a single `<script>` tag inside `index.html`.
- The `rules` array maps keywords (like `"hello"`, `"joke"`, `"time"`) to possible replies.
- If nothing matches, a random fallback reply is used.

## Customize it

Add your own rule by editing the `rules` array:

```js
{ triggers: ['weather'], replies: [
  "I can't check the weather yet, but you could hook me up to a weather API!"
]}
```

## Ideas to extend

- Connect it to a real AI API (like Claude) for smarter replies
- Add a typing sound effect
- Save chat history with localStorage
- Add light/dark mode toggle

## License

MIT — do whatever you'd like with this.
