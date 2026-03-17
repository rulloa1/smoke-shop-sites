# Smoke Shop Demo Sites

A collection of **ready-to-use, single-file website templates** for smoke shops — built to serve as polished sales pitch demos when pitching a new site to a potential smoke shop client.

Each template is a completely self-contained HTML file with no build step required. Just open it in a browser.

---

## 📂 Templates Available

| Template | File | Style | Primary Color |
|---|---|---|---|
| **Cloud Nine Smoke Shop** | `sites/cloud-nine-smoke-shop.html` | Dark stone (Premium) | Purple `#7c3aed` |
| **Verdant Smoke Shop** | `sites/verdant-smoke-shop.html` | Light organic (Eco-conscious) | Green `#16a34a` |

---

## 🚀 How to Use

1. **Clone this repo** (or download the HTML file directly):
   ```bash
   git clone https://github.com/rulloa1/smoke-shop-sites.git
   ```

2. **Open the HTML file** in any browser — no server needed:
   ```bash
   open sites/cloud-nine-smoke-shop.html
   ```
   Or simply double-click the file in your file manager.

3. **Host it for free** — upload to Netlify Drop, GitHub Pages, or any static host for a shareable demo link.

---

## 🎨 Customization

Each template is designed to be easy to customize for a specific client without any build tooling.

### Change the Business Name, Address & Phone

Open the HTML file and search for these values:

| What to change | Search for |
|---|---|
| Business name | `Cloud Nine Smoke Shop` |
| Address | `123 High St` / `Denver, CO 80203` |
| Phone | `(303) 555-0199` / `tel:3035550199` |
| Google Maps link | `https://maps.google.com/?q=123+High+St+Denver+CO` |
| Hours | `10:00 AM – 9:00 PM` / `11:00 AM – 7:00 PM` |

### Change the Brand Color

Each template defines a single CSS custom property at the top of the `<style>` block:

```css
:root {
  --primary-color: #7c3aed; /* 👈 Change this */
}
```

Swap this hex value to any color — the button, icon highlights, accent text, and hover effects will all update automatically.

**Color suggestions by vibe:**
- `#7c3aed` — Purple (premium, smoky)
- `#0ea5e9` — Sky blue (clean, modern)
- `#16a34a` — Green (natural, hemp-forward)
- `#dc2626` — Red (bold, energetic)
- `#d97706` — Amber (warm, welcoming)

### Change Services / Products

The services section contains 4 cards. Each card follows this structure:

```html
<div class="service-card ...">
  <div class="...icon wrapper...">
    <!-- Replace with your SVG icon -->
  </div>
  <div>
    <h3>Service Title</h3>
    <p>Description text.</p>
  </div>
</div>
```

### Swap Customer Reviews

Reviews are in the reviews section, each following this pattern:

```html
<div class="review-card ...">
  <div class="stars">★★★★★</div>
  <p>"Review text here."</p>
  <div>
    <p>Reviewer Name</p>
    <span>Time ago</span>
  </div>
</div>
```

---

## ➕ How to Add a New Template

1. **Copy an existing template** as your starting point:
   ```bash
   cp sites/cloud-nine-smoke-shop.html sites/my-new-shop.html
   ```

2. **Update all business details** (name, address, phone, hours, color).

3. **Add it to `index.html`** so it appears in the gallery — copy one of the existing demo cards and update the `href` and title.

4. **Add a row to the table** in this README.

---

## 🛠 Tech Stack

- **[Tailwind CSS CDN](https://cdn.tailwindcss.com)** — utility-first CSS, no build step
- **[Google Fonts — Inter](https://fonts.google.com/specimen/Inter)** — clean, modern typeface
- **Inline SVG icons** — no icon library dependency
- **Vanilla HTML/CSS** — zero JavaScript frameworks, zero dependencies

---

## 📄 License

Templates are demo assets — customize and use freely for client pitches.
