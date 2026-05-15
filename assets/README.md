# 📁 Assets Folder

Place your files here:

| File | Purpose | Size |
|------|---------|------|
| `profile.jpg` | Profile photo in About section | Square, min 400×400px |
| `og-cover.png` | LinkedIn / social sharing preview image | 1200×630px |

## How to add your photo locally

```bash
# Copy your photo to the assets folder
cp ~/Downloads/your-photo.jpg assets/profile.jpg

# Commit and push
git add assets/profile.jpg
git commit -m "📸 Add profile photo"
git push origin main
```

## og-cover.png tip
Create a simple branded card (e.g. in Canva) at 1200×630px with your name, title, and a dark background matching the portfolio theme.
