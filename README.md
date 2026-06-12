# 🎈 Premium Minimalist Blog Template

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: GitHub Pages](https://img.shields.io/badge/Hosting-GitHub%20Pages-blue.svg)](https://pages.github.com/)

A beautiful, hyper-lightweight, and fully responsive static HTML5/CSS3 personal blog template inspired by the famous tech-blog design of the Jekyll Chirpy theme. Built entirely without complex static site generators, dependencies, or bundlers. Fully optimized out-of-the-box for **GitHub Pages** hosting.

[Demo](https://ewewerban.github.io/post_template/)

---

## 📸 Preview

![Desktop Mockup](/assets/img/preview.png)
*Fully functional modern tech layout with side navigation.*

---

## ✨ Features

- ⚡ **Zero Setup & Bundler-Free:** No Jekyll, Node.js, or Ruby required. It runs purely on clean static HTML/CSS.
- 📱 **100% Responsive Design:** Desktop sticky sidebar seamlessly morphs into a mobile-friendly top bar navigation.
- 🛠️ **Chirpy Style Infoboxes:** Built-in beautiful Callout Alert classes (`info`, `tip`, `warning`, `danger`) for interactive post styling.
- 🔗 **Clean URL Structures:** Folder-based architecture allows clean address navigation (e.g., `domain.com/posts/git-guide/`).
- 🔒 **GitHub Pages Ready:** Pre-configured relative paths make deployment a one-click process.

---

## 🛠️ How to Use (Fork & Deploy)

### Step 1: Fork the Repository
Click the **Fork** button in the top-right corner of this page to create an independent copy of this project directly on your GitHub account.

### Step 2: Launch GitHub Pages
1. In your forked repository, go to the **Settings** tab.
2. Scroll down to the **Pages** menu on the left sidebar.
3. Under the **Build and deployment** section, select the `main` branch as your source.
4. Click **Save**. Within a minute, GitHub will provide a live public link to your new blog!

### Step 3: Customize Content & Media
Simply edit the core files directly through the GitHub web interface or clone them locally:
- **`index.html`** – Update your blog title, subtitle, and managing post preview list.
- **`style.css`** – Modify color codes, background configurations, or fonts.
- **`assets/img/`** – Drop your custom profile photo named as `logo.png` to automatically replace the avatar.

---

## 📝 Writing a New Post & Categories

To preserve clean URLs without a server framework, just follow these simple folder layout rules:

1. Create a new folder inside the `posts/` directory using standard web-slug naming (`posts/my-custom-guide/`).
2. Inside that folder, create an `index.html` file using any existing post file as a structural blueprint.
3. Link your post inside the root `index.html` file for the homepage timeline.
4. Open `categories/index.html` or `tags/index.html` to manually attach your newly created post to its respective group block.

---

## 💡 Using Premium Infoboxes

You can use custom markdown-like callout components directly inside any post body:

### Pro Tip Box
```html
<div class="callout tip">
    <div class="callout-title">💡 Pro Tip</div>
    <p>Your content text here...</p>
</div>
