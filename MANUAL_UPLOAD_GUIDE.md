# Manual Upload Guide - Fix Push Issues

The git push is failing due to SSL/network issues with large files. Here's how to manually upload the changes:

## Option 1: Upload via GitHub Web Interface (Recommended)

1. **Go to your repository**: https://github.com/juryiscoolman/WallStreetClash.com

2. **For each updated file, upload the new version**:
   - Click on the file (e.g., `index.html`)
   - Click the pencil icon (Edit)
   - Copy/paste the new content from your local files
   - Click "Commit changes"

3. **For new files** (`terms.html`, `privacy.html`, `images/ranks/*.png`):
   - Click "Add file" → "Upload files"
   - Drag and drop the files
   - Click "Commit changes"

## Option 2: Use GitHub Desktop App

1. Download GitHub Desktop: https://desktop.github.com
2. Add the repository
3. Commit and push through the GUI (handles large files better)

## Files That Need to Be Updated:

### Modified Files:
- `index.html` (updated with rank icons and new links)
- `styles.css` (updated with green/black theme)

### New Files:
- `terms.html` (Terms of Service)
- `privacy.html` (Privacy Policy)
- `images/ranks/` folder with all 24 rank icons

## Quick Fix - Just Upload Key Files

If you want the changes visible quickly, at minimum upload:
1. `styles.css` - This will show the green/black theme
2. `index.html` - This will show the rank icons

The Terms and Privacy pages can be added later if needed.

## After Upload

After uploading via web interface:
1. GitHub Pages should auto-update (may take 1-5 minutes)
2. Visit your site: https://juryiscoolman.github.io/WallStreetClash.com
3. Hard refresh (Ctrl+F5 or Cmd+Shift+R) to see changes
