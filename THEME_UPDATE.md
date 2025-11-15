# Documentation Theme Update

Your documentation has been updated with the **ReadTheDocs theme** - a professional, clean documentation style similar to Ollama's layout!

## What's Changed

✨ **Theme Improvements:**
- **ReadTheDocs theme** - Clean, professional look without the white header bar issue
- **Left sidebar navigation** - Main menu on the left (like Ollama docs)
- **Right sidebar TOC** - Page sections on the right for easy navigation
- **Sticky navigation** - Sidebar stays visible as you scroll
- **Modern color scheme** - Indigo primary color (#4f46e5) inspired by Ollama
- **Enhanced typography** - Better spacing and readability
- **Dark code blocks** - Modern dark theme for code
- **Improved tables** - Better styling with hover effects
- **Responsive design** - Works great on mobile and desktop
- **Clean header** - No unwanted white bars, minimal top navigation

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

The documentation is automatically deployed to GitHub Pages when you push to the `main` branch using the GitHub Actions workflow.

### Manual Deployment (if needed)

```bash
mkdocs gh-deploy
```

## Layout

```
┌─────────────────────────────────────────────────────────┐
│ Navigation Bar (Minimal header)                          │
├──────────────────────┬──────────────────────┬────────────┤
│                      │                      │            │
│  Left Sidebar        │   Main Content       │  Right TOC │
│  (Navigation Menu)   │   (Article)          │  (Sections)│
│                      │                      │            │
└──────────────────────┴──────────────────────┴────────────┘
```

## Customization

### Colors
Edit `docs/overrides/assets/stylesheets/custom.css` to change:
- Primary color (currently indigo `#4f46e5`)
- Text colors
- Background colors
- Border colors

### Logo
Update in `mkdocs.yml`:
```yaml
theme:
  logo: https://your-logo-url
```

### Navigation Structure
Modify the `nav` section in `mkdocs.yml` to reorganize your documentation.

### Font Changes
Edit the Google Fonts link in `docs/overrides/main.html`

## Features

- ✅ Clean sidebar navigation (collapsible)
- ✅ Sticky sidebar for easy navigation
- ✅ Right-side table of contents
- ✅ Search functionality
- ✅ Responsive design
- ✅ Code syntax highlighting
- ✅ Custom styling (admonitions, tables, links)
- ✅ Integrated GitHub link
- ✅ Next/Previous page navigation
- ✅ Mobile-friendly

## Learn More

- [ReadTheDocs Theme Documentation](https://www.mkdocs.org/user-guide/choosing-your-theme/#readthedocs)
- [MkDocs Official Documentation](https://www.mkdocs.org/)

