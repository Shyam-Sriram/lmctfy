# lmctfy — Let Me Claude That For You

> *For when asking Claude was clearly the move.*

A passive-aggressive link generator in the spirit of [lmgtfy](https://github.com/NatoBoram/lmgtfy), but for Claude.

## How it works

1. You type a question someone should have just asked Claude
2. You get a shareable URL: `https://yourdomain.com/?q=how+do+I+exit+vim`
3. They open it, watch it get typed into a fake Claude chat window
4. They get redirected to [claude.ai](https://claude.ai) with the question pre-filled
5. They feel mildly called out

## Local development

No build step needed. Just open `index.html` in a browser.

```bash
open index.html
# or
python3 -m http.server 8080
```

## Customization

- **Snarky messages** — edit the `SNARKS` array in `index.html`
- **Claude replies** — edit the `CLAUDE_REPLIES` array
- **Countdown duration** — change the `5` in `startCountdown()`
- **Colors** — tweak CSS variables in `:root`

## License

I don't know claude built this.
