# praween.space — Static Site Migration

## Site Structure

```
praween-site/
├── index.html          # Homepage
├── about.html          # About me
├── research.html       # My Research (with Th/En toggle)
├── genealogy.html      # Ph.D. Genealogy
├── gallery.html        # Ceiling photography gallery
├── contact.html        # Contact page (uses Formspree)
├── CNAME               # Custom domain for GitHub Pages
├── css/
│   └── style.css       # Main stylesheet
└── images/             # ⚠️ YOU NEED TO ADD IMAGES HERE
    ├── hero-bg.jpg              # Homepage hero background
    ├── praween-portrait.jpg     # About page portrait photo
    ├── cmb-planck.jpg           # CMB map from PLANCK
    ├── polarbear-telescope.jpg  # POLARBEAR telescope photo
    ├── polarization-modes.jpg   # E-mode/B-mode diagram
    ├── simons-array.jpg         # Simons Array photo
    ├── chile-map.jpg            # Chile site location map
    ├── genealogy/               # Genealogy portraits
    │   └── leibniz.jpg          # (and other portraits)
    └── ceiling/                 # Gallery photos
        ├── dsc_0186.jpg
        ├── dsc_0027.jpg
        └── ... (22 photos total)
```

## Deployment Steps

### 1. Download Images from WordPress

You need to download your images from WordPress and place them in the `images/` folder.

- Go to your WordPress Dashboard → Media → Library
- Download each image and place in the correct subfolder

### 2. Set Up GitHub Repository

1. Create a new GitHub repository (e.g., `praween.github.io` or `praween-site`)
2. Push all files to the repository
3. Go to Settings → Pages → Source: Deploy from branch (main)

### 3. Set Up Formspree (for Contact Form)

1. Go to https://formspree.io and create a free account
2. Create a new form and get your form ID
3. Replace `YOUR_FORM_ID` in `contact.html` with your actual form ID

### 4. Configure Cloudflare DNS

1. In Cloudflare, update DNS records:
   - Add a CNAME record: `praween.space` → `yourusername.github.io`
   - Or if using apex domain, add A records pointing to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
2. Enable "Proxied" status for the record
3. In GitHub repo Settings → Pages → Custom domain: enter `praween.space`
4. Enable "Enforce HTTPS"

### 5. Update Social Links

Update the Twitter and Instagram URLs in each HTML file's header to your actual profile URLs.

## Notes

- The contact form uses Formspree (free tier: 50 submissions/month)
- The Thai content section on the research page has a placeholder — add your Thai content
- Gallery images use lazy loading for performance
- The site is fully responsive
