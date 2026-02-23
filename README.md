# enovy
Elisabeth Novy Website
---

## How to Add Your Photos

Create a folder called `images/` in the same directory as the HTML files and place your photos there. Then reference them in the HTML using `src="images/your-photo.jpg"`.

### Images to replace (in order of importance):

**index.html (Works page)**
| Filename | Where it appears | Notes |
|---|---|---|
| `images/hero.jpg` | Full-screen hero image | Landscape, strong portrait shot |
| `images/work-01.jpg` through `work-06.jpg` | Featured works grid | Portrait orientation (3:4 ratio) |
| `images/quote-bg.jpg` | Quote band background | Landscape, moody/atmospheric |
| `images/art-01.jpg` through `art-03.jpg` | Painted photography section | Any ratio |

**services.html**
| Filename | Where it appears |
|---|---|
| `images/service-01.jpg` through `service-06.jpg` | Service cards (portrait orientation) |
| `images/services-bg.jpg` | CTA quote band background |

**about.html**
| Filename | Where it appears |
|---|---|
| `images/elisabeth.jpg` | Large portrait of Elisabeth (left column) |
| `images/art-painted-01.jpg` through `art-painted-03.jpg` | Painted photography gallery |
| `images/contact-img.jpg` | Contact section right column |

---

## Text Placeholders to Fill In

Search for `<!-- PLACEHOLDER:` in each HTML file to find every text spot that needs your content.

Also replace:
- `hello@elisabethnovy.com` → your actual email
- `@yourhandle` / `https://instagram.com/YOURHANDLE` → your Instagram
- The LinkedIn `#` → your LinkedIn URL
- `© 2025 Elisabeth Novy` → adjust year if needed

---

## How to Publish on GitHub Pages (Free)

1. Create a free account at [github.com](https://github.com) if you don't have one
2. Create a new repository — name it **`username.github.io`** (replace `username` with your GitHub username) for a free custom URL, OR any other name
3. Upload all files: `index.html`, `services.html`, `about.html`, `style.css`, and the entire `images/` folder
4. Go to **Settings → Pages** in your repository
5. Under "Source", select **Deploy from a branch** → choose `main` → `/ (root)` → Save
6. Your site will be live at `https://username.github.io` within a few minutes

---

## Tips for 102 Photos

For the full portfolio, you can:
- Show 6–12 **hero/featured** works on the home page
- Create additional gallery pages (e.g. `gallery.html`) with a CSS grid of all photos
- Organize by series/category using the `photo-caption` labels

The current grid on `index.html` shows 6 works. Simply copy/paste additional `<div class="photo-item">` blocks to add more.

---

## Fonts Used
- **Cormorant Garamond** – elegant serif display font (loaded from Google Fonts)
- **Jost** – clean geometric sans-serif for body text (loaded from Google Fonts)

Both load automatically via the internet. No installation needed.
