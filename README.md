# jishnume.github.io

Personal academic site — written in Markdown, rendered by Jekyll via GitHub Pages.
No HTML knowledge needed to edit it.

---

## How to update the site

Everything is a `.md` (Markdown) file. Edit it on GitHub directly:

1. Click any `.md` file in the repo
2. Click the pencil icon (top right) to edit
3. Make your changes
4. Click **Commit changes** at the bottom

Your change is live within ~30 seconds.

---

## File map

```
_config.yml          ← Site title, theme, nav order — edit once, rarely again
index.md             ← Home page
research.md          ← Research overview
publications.md      ← Papers and preprints
blog.md              ← Notes index (links to individual notes in Blog/)
teaching.md          ← Teaching
cv.md                ← CV
contact.md           ← Contact
cv.pdf               ← Upload your actual CV here
Blog/                ← Individual note files go here
```

---

## Markdown cheatsheet (the 10% you'll use 90% of the time)

```markdown
## Section heading
### Subsection heading

Normal paragraph text. Just type.

**bold text**
*italic text*
`inline code`

- bullet point
- another bullet

[link text](https://example.com)
[link to another page on your site](../research/)

---      ← horizontal rule / divider
```

---

## Adding a new blog note

1. Create a new file in `Blog/` — e.g. `Blog/my-new-note.md`
2. Paste this at the very top (called "front matter"):

```
---
layout: page
title: My note title
---
```

3. Write your note in Markdown below that.
4. Add a link to it in `blog.md` so people can find it.

---

## Changing the theme colour

In `_config.yml`, change `skin: classic` to one of:

- `classic` — white, minimal
- `dark` — dark background
- `solarized` — warm off-white
- `solarized-dark` — dark warm

---

## Enabling GitHub Pages (one-time setup)

If the site isn't live yet:

1. Go to **Settings → Pages** in your GitHub repo
2. Under **Source**, choose **Deploy from a branch**
3. Branch: `main`, Folder: `/ (root)`
4. Click **Save**

Site will be live at `https://jishnume.github.io` within a minute.
