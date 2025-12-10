# Public Image Hosting

This repository serves as a public image hosting solution using GitHub Pages for the Center for Conscious Alchemy.

## 🌐 Live Site

Visit [https://center-for-conscious-alchemy.github.io/public/](https://center-for-conscious-alchemy.github.io/public/) to access the hosted images.

## 📖 Usage

All images stored in the `/images` directory are publicly accessible via GitHub Pages. 

### URL Pattern

```
https://center-for-conscious-alchemy.github.io/public/images/[your-image-path]
```

### Examples

- `https://center-for-conscious-alchemy.github.io/public/images/logo.png`
- `https://center-for-conscious-alchemy.github.io/public/images/banners/hero.jpg`
- `https://center-for-conscious-alchemy.github.io/public/images/icons/icon.svg`

## 📁 Directory Structure

```
public/
├── images/           # All images go here
│   ├── logos/       # Example subdirectory
│   ├── banners/     # Example subdirectory
│   └── icons/       # Example subdirectory
├── index.html       # Landing page
├── _config.yml      # Jekyll configuration
└── README.md        # This file
```

## ➕ Adding Images

1. Clone this repository:
   ```bash
   git clone https://github.com/Center-for-Conscious-Alchemy/public.git
   cd public
   ```

2. Add your image(s) to the `images/` directory:
   ```bash
   cp /path/to/your/image.png images/
   # Or organize in subdirectories
   mkdir -p images/logos
   cp /path/to/logo.png images/logos/
   ```

3. Commit and push your changes:
   ```bash
   git add images/
   git commit -m "Add new images"
   git push origin main
   ```

4. Wait a few moments for GitHub Pages to deploy (usually 1-2 minutes)

5. Access your image at:
   ```
   https://center-for-conscious-alchemy.github.io/public/images/your-image.png
   ```

## ⚙️ GitHub Pages Configuration

This repository uses GitHub Pages with Jekyll. The configuration is in `_config.yml`.

### Enabling GitHub Pages

To enable GitHub Pages for this repository:

1. Go to repository **Settings** → **Pages**
2. Under **Source**, select the branch to deploy (typically `main`)
3. Click **Save**
4. GitHub Pages will be available at `https://center-for-conscious-alchemy.github.io/public/`

## 📝 Notes

- Images are cached by GitHub's CDN for fast access
- Supported formats: PNG, JPG, GIF, SVG, WebP, and more
- Recommended to optimize images before uploading to reduce load times
- Keep image filenames lowercase and use hyphens instead of spaces

## 📄 License

Public domain - images hosted here are meant for public use by Center for Conscious Alchemy.