# Flow — Digital Product Studio

A cinematic, single-brand marketing site for a digital product studio. Built as three static HTML pages sharing one design system — black / electric-blue / signal-red, video-backed heroes, and hover-driven micro-interactions.

No build step, no framework, no dependencies beyond Google Fonts and Font Awesome (both via CDN). Drop the files on any static host and it runs.

---

## 📁 File structure

All CSS is inline in each page's `<style>` block, and the contact page carries its own small `<script>` for the form. There is nothing to compile or install.

---

## 🚀 Running locally

Because everything is static, any of these work:

**Option A — just open it**
Double-click `index.html`. Everything loads, though some browsers restrict `autoplay` and local `file://` video playback.

**Option B — local server (recommended)**
```bash
# Python 3
python -m http.server 8000

# or Node
npx serve .
