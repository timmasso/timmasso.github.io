# timmasso.github.io

Personal website and portfolio for Timothy Masso.

## Repository Structure

This Jekyll site is organized with the following clean folder structure:

### Collections
- `_aboutme/` - About me content collection
- `_dataprojects/` - Data science and analytics projects
- `_performances/` - Performance and music content
- `_typewriters/` - Typewriter collection content
- `_posts/` - Blog posts (moved from projects/_posts for standard Jekyll structure)

### Jekyll Directories
- `_data/` - Site data files
- `_includes/` - Reusable template partials
- `_layouts/` - Page layouts and templates

### Assets
- `assets/` - Static assets organized into subfolders:
  - `css/` - Stylesheets
  - `js/` - JavaScript files
  - Various project-specific directories and media files

### Configuration & Pages
- `_config.yml` - Jekyll configuration
- `index.markdown` - Homepage
- `about.markdown` - About page
- `new_school.html` - New School related content
- `404.html` - Error page
- `Gemfile` - Ruby dependencies

### GitHub
- `.github/workflows/` - GitHub Actions for CI/CD
- `.vscode/` - VS Code settings
- `.gitignore` - Git ignore rules

## Recent Changes

- ✅ Removed unnecessary files (`indexgood.txt`, `refrenacepostmarkdown.txt`)
- ✅ Moved blog posts from `projects/_posts/` to root `_posts/` directory for standard Jekyll structure
- ✅ Cleaned up repository organization
- ✅ Updated documentation

## Development

This is a Jekyll site. To run locally:

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions when changes are pushed to the main branch.
