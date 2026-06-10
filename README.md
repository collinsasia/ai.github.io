# Asia Collins — Portfolio Website

A portfolio resume website for the Applied AI Analyst role at Nymbus.

## 🚀 Deploy to GitHub Pages (3 steps)

1. **Create a new GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it exactly: `your-username.github.io`
   - Set it to **Public**
   - Click **Create repository**

2. **Upload the file**
   - Click **Add file → Upload files**
   - Drag `index.html` into the upload area
   - Click **Commit changes**

3. **Enable GitHub Pages**
   - Go to **Settings → Pages**
   - Under **Source**, select `main` branch and `/ (root)` folder
   - Click **Save**
   - Your site will be live at `https://your-username.github.io` within ~60 seconds ✅

---

## 📁 File structure

```
/
└── index.html   ← entire website (single file, no dependencies)
└── README.md
```

No build tools, no frameworks, no npm install. Everything is self-contained.

---

## ✏️ How to update content

All content is in `index.html`. Search for these sections:

| Section | Search for |
|---|---|
| Name / title | `Asia Collins` |
| Contact info | `collinsasiatech@gmail.com` |
| Metrics | `metric-num` |
| Hero badges | `hero-badges` |
| About text | `id="about"` |
| Experience | `id="experience"` |
| Skills | `id="skills"` |
| Typewriter phrases | `const phrases = [` |

---

## 🎨 Design tokens (colors)

Edit the `:root` block near the top of `index.html`:

```css
--navy:      #0F2744;   /* primary dark background */
--teal:      #00C2A8;   /* accent color */
--off-white: #F7F9FC;   /* page background */
```

---

## 📱 Responsive

Works on mobile, tablet, and desktop. The terminal card hides on mobile to keep things clean.
