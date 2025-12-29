# VentSnap - Floor Vent Attachment System

Open-source 3D printable attachments for standard floor vents.

![VentSnap](assets/images/hero-placeholder.jpg)


## Products

### Sheet Fort Clip Attachment
Turn any floor vent into a sheet fort anchor point. Perfect for building epic indoor forts that stay warm and cozy.

### 4" Round Duct Adapter  
Connect standard dryer vent hoses to any floor register. Redirect airflow to home offices, workshops, or anywhere you need it.

## Quick Start

### Building the Site

1. Install Jekyll and dependencies:
   ```bash
   bundle install
   ```

2. Serve locally:
   ```bash
   bundle exec jekyll serve
   ```

3. Visit `http://localhost:4000`

### Adding Your Files

1. Place your STL/STEP files in `assets/models/`:
   - `sheet-fort-clip.stl`
   - `sheet-fort-clip.step`
   - `sheet-fort-clip.3mf`
   - `duct-adapter-4in.stl`
   - `duct-adapter-4in.step`
   - `duct-adapter-4in.3mf`

2. Add product images to `assets/images/`:
   - `sheet-fort-clip-hero.jpg`
   - `sheet-fort-clip-installed.jpg`
   - `duct-adapter-hero.jpg`
   - etc.

3. Rebuild the site

## Directory Structure

```
vent-attachment-site/
├── _config.yml           # Site configuration
├── _data/
│   ├── reviews.yml       # Customer reviews
│   └── use_cases.yml     # Use case stories
├── _includes/
│   ├── header.html
│   └── footer.html
├── _layouts/
│   ├── default.html
│   └── product.html
├── _products/            # Product pages
│   ├── sheet-fort-clip.md
│   └── round-duct-adapter.md
├── assets/
│   ├── css/main.css
│   ├── images/           # Add your images here
│   └── models/           # Add your STL/STEP files here
├── pages/
│   ├── products.html
│   ├── use-cases.html
│   ├── printing-guide.html
│   └── about.html
└── index.html
```

## Customization

### Site Settings
Edit `_config.yml` to update:
- Site title and description
- Repository URL
- Author information

### Reviews
Edit `_data/reviews.yml` to add/modify customer reviews.

### Use Cases
Edit `_data/use_cases.yml` to add/modify use case stories.

### Products
Add new products by creating markdown files in `_products/` following the existing format.

## Deployment

### GitHub Pages
1. Push to GitHub
2. Enable GitHub Pages in repository settings
3. Select the branch to deploy

### Netlify
1. Connect your repository
2. Build command: `jekyll build`
3. Publish directory: `_site`

### Manual
1. Build: `bundle exec jekyll build`
2. Upload `_site/` contents to your web server

## License

MIT License - See LICENSE file for details.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

Issues and feature requests welcome!
