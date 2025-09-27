# timmasso.github.io
Personal website and portfolio for Timothy Masso.

## Repository Structure
This Jekyll site is organized with the following folder structure:

### Collections
- `_aboutme/` - About me content collection
- `_dataprojects/` - Data science and analytics projects
- `_performances/` - Performance and music content
- `_typewriters/` - Typewriter collection content

### Projects
- `projects/_posts/` - Blog posts in their original location

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
- `indexgood.txt` - Index template file (restored)
- `about.markdown` - About page
- `new_school.html` - New School related content
- `refrenacepostmarkdown.txt` - Reference post markdown template (restored)
- `404.html` - Error page
- `Gemfile` - Ruby dependencies

### GitHub
- `.github/workflows/` - GitHub Actions for CI/CD
- `.vscode/` - VS Code settings
- `.gitignore` - Git ignore rules

## Recent Restoration
✅ **Repository structure restored to previous state:**
- ✅ Restored `indexgood.txt` file to root directory
- ✅ Restored `refrenacepostmarkdown.txt` file to root directory
- ✅ Moved blog posts back from root `_posts/` to `projects/_posts/` directory
- ✅ Maintained existing `about.markdown` and `new_school.html` in their locations
- ✅ Preserved all asset organization and configuration files
- ✅ Updated documentation to reflect restored structure

## Development
This is a Jekyll site. To run locally:
```bash
bundle install
bundle exec jekyll serve
```
The site will be available at http://localhost:4000.

## Deployment
The site is automatically deployed to GitHub Pages via GitHub Actions when changes are pushed to the main branch.

<!-- Rebuild trigger: 2025-09-26 20:27 EDT -->
