# Photo Gallery

A beautiful, responsive photo gallery showcasing 46 curated photos.

## Features

- 🖼️ **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- 🎨 **Modern UI** - Dark theme with gradient accents
- ⚡ **Smooth Animations** - Hover effects and transitions
- 🎯 **Full-screen Viewer** - Click any photo to view in fullscreen
- ⌨️ **Keyboard Controls** - Use arrow keys to navigate, ESC to close
- 📱 **Lazy Loading** - Images load as you scroll for better performance

## Local Setup

1. Clone this repository
2. Open `index.html` in your browser
3. Browse and enjoy the photos!

## Publishing to GitHub Pages

### Option 1: Using gh-pages Branch (Recommended)

1. Create a new branch called `gh-pages`:
   ```bash
   git checkout --orphan gh-pages
   git reset --hard
   git commit --allow-empty -m "Initial commit"
   git push -u origin gh-pages
   ```

2. Switch back to main branch:
   ```bash
   git checkout main
   ```

3. Go to your GitHub repository settings:
   - Navigate to **Settings** → **Pages**
   - Under "Source", select branch **gh-pages**
   - Click Save

4. Your gallery will be live at: `https://yourusername.github.io/your-repo-name`

### Option 2: Using Main Branch

1. In GitHub repository settings:
   - Navigate to **Settings** → **Pages**
   - Under "Source", select branch **main** and folder **root** (/)
   - Click Save

2. Your gallery will be live at: `https://yourusername.github.io/your-repo-name`

### Option 3: Using docs Folder

1. Move all files to a `docs/` folder
2. In GitHub repository settings:
   - Navigate to **Settings** → **Pages**
   - Under "Source", select branch **main** and folder **/docs**
   - Click Save

## Repository Structure

```
├── index.html          # Main gallery page
├── Selected/           # Photo folder (46 images)
├── README.md          # This file
└── .git/              # Git repository
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Notes

- All 46 photos are automatically loaded on page startup
- Photos are displayed in a responsive grid layout
- Click any photo to open fullscreen viewer
- Use arrow buttons or keyboard arrows to navigate between photos
- Press ESC or click outside the image to close fullscreen viewer

---

**Created with ❤️** - Simple, fast, and beautiful photo gallery