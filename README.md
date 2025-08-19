# 🏷 Shopify Top Promo Banner (Dawn Theme)

> ✅ **Dawn‑first**: This section ships with a ready example for Dawn’s `header-group.json`.  

A fully customizable **Top Promo Banner** section for Shopify themes.  
Built to solve the limitations of Shopify’s **native announcement bar**, this section adds **dynamic content, rich text, inline links, font controls, and optional images** — while keeping design clean and responsive.

---

## 🚨 Problem Statement
Shopify’s default **announcement bar** is limited:
- Only supports a single plain text line.
- No **bold, italic, links, or inline formatting**.
- No control over **font sizes** or spacing.
- Lacks flexibility for adding **images, multiple lines, or styled calls‑to‑action**.

For merchants and developers who need **marketing flexibility** and **modern UI control**, these limitations slow down customization and require hacky workarounds.

---

## ✅ Solution
This **Top Promo Banner** section introduces:
- 🎨 **Rich Text Support** → Bold, italic, links, lists, and more for titles, sub‑headlines, and optional third lines.
- 🔠 **Font Size Controls** → Adjustable sliders for each text line.
- 🔗 **Configurable Inline Link** → Inline link text + URL (editor‑friendly), rendered with consistent styling.
- 🖼 **Optional Right‑Aligned Image** → Great for small logos or product badges.
- ⚡ **Responsive & Clean** → Liquid + CSS grid, optimized for desktop/mobile.

---

## 📸 Demo
Example output:

<img width="1351" height="188" alt="Screenshot 2025-08-19 at 9 34 23 AM" src="https://github.com/user-attachments/assets/11a8e3be-604e-4134-a1c3-41f4cebcd7d3" />

---

## 📂 File Structure

shopify-top-promo-banner/
├─ sections/
│ └─ top-promo-banner.liquid # The reusable section (core file)
│ └─ header-group.json.sample # Dawn-ready example to merge with your theme
├─ LICENSE
└─ README.md


---

## 🚀 Installation (Dawn)

> ℹ️ If your theme already has custom header settings, **merge** the example into your existing `sections/header-group.json` instead of overwriting.

**Before you start:** Duplicate your live theme (Online Store → Themes → … → Duplicate).

### Step 1 — Add the section
Copy `sections/top-promo-banner.liquid` into your theme’s `/sections` folder.

### Step 2 — Register the section in the header group
Open your theme’s `sections/header-group.json` and:

1. Add the section to the `"header-group.json"` object:
   ```jsonc
   "top_promo_banner": {
     "type": "top-promo-banner",
     "settings": {}
   }

👉 You can also copy and paste from sections/header-group.json and merge it with your current file. Note if you have the annoucnment feature enable this will hide it. 

### Step 2 — Customize in the Theme Editor

Go to Online Store → Customize and edit the Top Promo Banner settings:
- Title (line 1) → rich text, always rendered bold
- Sub-headline (line 2) → rich text, rendered normal (no italics)
- Inline link text + URL
- Font sizes (title + sub-headline)
- Colors (background, text, link)
- Optional third line + right image

<img width="299" height="795" alt="Screenshot 2025-08-19 at 9 52 18 AM" src="https://github.com/user-attachments/assets/9d1de807-9db0-43bc-a107-5236a7e2175a" />



