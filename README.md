# Essence of You – Counseling & Consulting

A professional single-page website for **Essence of You Counseling and Consulting, LLC** — a mental health teletherapy practice offering counseling, supervision, and consulting services.

## 🌸 Live Site

Deploy via **GitHub Pages** (see below) or any static host.

---

## 📁 File Structure

```
essence-of-you/
├── index.html   # Complete website (all CSS & JS inline)
└── README.md
```

Everything is self-contained in `index.html` — no build step, no dependencies, no Node.js required.

---

## 🚀 Deploy to GitHub Pages

1. **Create a new GitHub repository** (e.g. `essence-of-you`)
2. **Upload both files** (`index.html` and `README.md`) to the repo root
3. Go to **Settings → Pages**
4. Under *Source*, select **Deploy from a branch**
5. Choose branch: `main` · folder: `/ (root)` → click **Save**
6. Your site will be live at:
   ```
   https://<your-username>.github.io/essence-of-you/
   ```

> 💡 **Custom domain**: In Settings → Pages → Custom domain, enter your domain (e.g. `essenceofyou.care`), then add a `CNAME` DNS record pointing to `<your-username>.github.io`.

---

## ✏️ Editing Content (Built-in CMS)

Click the **✏️ button** in the bottom-right corner of the live site to open the content editor. You can edit:

| Tab | Editable Content |
|-----|-----------------|
| Hero | Headline, sub-text, stats, card text |
| Services | Titles, descriptions, pricing |
| About | Therapist name, credentials, bio, focus areas |
| Quote | Inspirational quote & attribution, contact text |

Changes are saved to browser `localStorage` and persist across page reloads.

> **To make permanent edits**, open `index.html` in any text editor and update the relevant HTML directly. All content sections have clear `id` attributes for easy finding.

---

## 🎨 Customization

All design tokens are CSS variables at the top of the `<style>` block:

```css
:root {
  --sage:    #7a9e7e;   /* primary green */
  --violet:  #6b5b8a;   /* accent purple */
  --cream:   #f7f3ee;   /* background */
  --ink:     #2a2420;   /* text */
  /* ... */
}
```

Change these to instantly retheme the entire site.

---

## 📄 License

© 2025 Essence of You Counseling & Consulting, LLC. All rights reserved.
