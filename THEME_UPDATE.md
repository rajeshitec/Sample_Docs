# Documentation Theme Update

Your documentation has been updated with a modern theme inspired by Ollama's docs design!

## What's Changed

✨ **Theme Improvements:**
- Modern Material Design theme with enhanced typography
- Indigo color scheme inspired by Ollama's documentation
- Sticky navigation tabs for better UX
- Improved code blocks with syntax highlighting
- Better responsive design
- Dark/light mode toggle
- Enhanced tables and admonitions styling

## Building Locally

### Prerequisites
- Python 3.8+
- pip

### Setup

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Build the documentation:**
   ```bash
   mkdocs build
   ```

3. **Serve locally (with live reload):**
   ```bash
   mkdocs serve
   ```
   
   Then open `http://localhost:8000` in your browser

## Deploying to GitHub Pages

The documentation is automatically deployed to GitHub Pages when you push to the `main` branch. The GitHub Actions workflow in `.github/workflows/deploy.yml` handles the build and deployment.

### Manual Deployment (if needed)

```bash
mkdocs gh-deploy
```

## Customization

### Colors
Edit `docs/overrides/assets/stylesheets/custom.css` to change:
- Primary color (currently indigo `#4f46e5`)
- Accent colors
- Font choices

### Logo & Favicon
Update these in `mkdocs.yml`:
```yaml
theme:
  logo: https://your-logo-url
  favicon: https://your-favicon-url
```

### Navigation
Modify the `nav` section in `mkdocs.yml` to reorganize your documentation structure.

## Features Enabled

- ✅ Sticky tabs navigation
- ✅ Integrated table of contents
- ✅ Search with highlighting
- ✅ Code copying
- ✅ Code annotations
- ✅ Content tabs with linked state
- ✅ Tooltips
- ✅ Auto-hiding header
- ✅ Instant page loading

## Learn More

- [Material for MkDocs Documentation](https://squidfunk.github.io/mkdocs-material/)
- [MkDocs Official Documentation](https://www.mkdocs.org/)
