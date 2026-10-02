# madhuwrites ✦

A whimsical, luxury-inspired poetry website for GitHub Pages.

## Add or edit your poems

You no longer need to edit `index.html` to add poems.

Open **`poems.js`** and add another object inside the `poems` list:

```js
{
  title: "Your poem title",
  category: "longing",
  symbol: "☾",
  tone: "blue",
  excerpt: "A short description that appears on the card.",
  poem: "Your first line.\nYour second line.\n\nA new stanza."
}
```

Available card tones: `blue`, `lilac`, `pink`, `cream`.

You can use any category you like: `love`, `longing`, `grief`, `hope`, `distance`, etc. The website automatically creates category filters.

## GitHub Pages

Upload/replace these files in the **root** of your repository:

- `index.html`
- `style.css`
- `poems.js`

Keep `index.html` named exactly `index.html` and `style.css` exactly `style.css`.

If you use the music button, add your own `music.mp3` file to the same root folder.
