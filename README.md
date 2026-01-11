# MusicBox Product Page

Static product page for the MusicBox ESP32-S3 Music Display System.

## GitHub Pages Setup

To deploy this site on GitHub Pages:

1. **Push to GitHub** (if not already done):
   ```bash
   git add web/
   git commit -m "Add product page"
   git push origin main
   ```

2. **Configure GitHub Pages**:
   - Go to your repository on GitHub
   - Navigate to Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Under "Branch", select `main` and `/web` folder
   - Click Save

3. **Access your site**:
   - Your site will be available at: `https://yourusername.github.io/musicbox/`
   - GitHub will automatically build and deploy when you push changes

## Alternative: Root Directory Deployment

If you prefer to deploy from the root directory:

1. Move `web/index.html` and `web/styles.css` to the root directory
2. Update the download link in `index.html` from `../windows/dist/MusicBox.exe` to `windows/dist/MusicBox.exe`
3. In GitHub Pages settings, select `/` (root) instead of `/web`

## Local Development

To preview locally, simply open `index.html` in your browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Then visit http://localhost:8000
```

## Files

- `index.html` - Main product page
- `styles.css` - Styling and responsive design
- `.nojekyll` - Prevents Jekyll processing on GitHub Pages

## Updating Content

To add product photos, replace the placeholder divs in the "Photos Section" with actual image tags:

```html
<img src="path/to/photo.jpg" alt="Description">
```

To update links, modify the GitHub repository links in the footer section.
