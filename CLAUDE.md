# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based academic portfolio website using the Minimal Mistakes theme, hosted on GitHub Pages. It serves as a professional showcase for academic work, research, publications, and projects.

## Technology Stack

- **Static Site Generator**: Jekyll 4.3+
- **Theme**: Minimal Mistakes 4.27.1 (remote theme)
- **Hosting**: GitHub Pages
- **Ruby Dependencies**: Managed via Gemfile and Bundler
- **Content Format**: Markdown with YAML front matter

## Development Commands

### Local Development
```bash
# Install Ruby dependencies
bundle install

# Serve site locally with auto-reload
bundle exec jekyll serve

# Build site for production
bundle exec jekyll build

# View at http://localhost:4000
```

### Deployment
- **Automatic**: Push to `main` branch triggers GitHub Pages deployment
- **Manual**: No manual deployment commands needed

## Architecture

### Site Structure
```
├── _config.yml              # Main Jekyll configuration
├── _data/
│   └── navigation.yml       # Site navigation menu
├── _pages/                  # Content pages (About, Research, etc.)
├── assets/images/           # Profile photos and media
├── index.md                 # Homepage with feature rows
├── Gemfile                  # Ruby dependencies
└── Resume_*.pdf            # CV/Resume files
```

### Content Organization
- **Homepage**: `index.md` with feature rows and quick links
- **Static Pages**: All content pages in `_pages/` directory
- **Navigation**: Configured in `_data/navigation.yml`
- **Author Profile**: Defined in `_config.yml` under `author:` section

### Page Types
- **about.md**: Background, education, skills
- **research.md**: Current and past research projects  
- **projects.md**: Technical projects and repositories
- **publications.md**: Academic papers and presentations
- **contact.md**: Contact information and office hours
- **test.md**: Debug/testing page

## Configuration

### Site Settings (`_config.yml`)
- **Title/Author**: Bryce Wang, Stanford PhD student
- **Theme**: Minimal Mistakes default skin
- **Plugins**: Pagination, sitemap, feed, include-cache
- **Social Links**: Twitter, GitHub, Email configured in author section

### Content Management
- **Format**: Markdown files with YAML front matter
- **Layout**: All pages use `single` layout with author profile
- **URLs**: Clean permalinks (/:categories/:title/)

## Key Files to Modify

### For Content Updates:
- `_pages/*.md` - All main content pages
- `index.md` - Homepage feature rows and quick links
- `_config.yml` - Site metadata and author information
- `_data/navigation.yml` - Menu structure

### For Theme/Style Changes:
- `_config.yml` - Theme skin and configuration
- `assets/` - Custom CSS/JS (if needed)
- Theme overrides via `_layouts/`, `_includes/`, `_sass/` (if created)

## Development Notes

- No build tools (webpack, npm, etc.) - pure Jekyll
- No testing framework configured
- No linting tools configured  
- Content is version controlled; site builds automatically on push
- Mobile-responsive via Minimal Mistakes theme
- SEO optimized with automatic sitemap generation

## Common Tasks

### Adding Content:
1. Create/edit Markdown files in `_pages/`
2. Update navigation in `_data/navigation.yml` if needed
3. Commit and push - site rebuilds automatically

### Theme Customization:
1. Override theme files by creating local copies
2. Modify `_config.yml` for theme settings
3. Add custom CSS in `assets/css/main.scss`

### Profile Updates:
1. Replace `assets/images/bio-photo.jpg`
2. Update `author:` section in `_config.yml`
3. Replace resume PDF files