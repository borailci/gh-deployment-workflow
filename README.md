# GitHub Deployment Workflow

This project demonstrates how to set up a GitHub Actions workflow to automatically deploy a Jekyll-based personal portfolio website to GitHub Pages. The deployment is triggered whenever specific files are changed on the `main` branch.

## Features

- **Jekyll Static Site Generator**: Professional portfolio site with blog functionality
- **Automated Deployment**: GitHub Actions workflow triggers on file changes
- **Responsive Design**: Modern, mobile-friendly layout
- **Blog Posts**: Markdown-based content management
- **Custom Styling**: Professional DevOps-themed design

## Structure

- `index.md` - Homepage content
- `about.md` - About page
- `_posts/` - Blog posts in Markdown format
- `_layouts/` - Jekyll layout templates
- `_config.yml` - Jekyll configuration
- `assets/` - CSS and other assets
- `.github/workflows/deploy.yml` - GitHub Actions deployment workflow

## Local Development

To run locally:

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000` to view the site.

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch. The workflow monitors these paths:
- `index.md`
- `_posts/**`
- `_config.yml`
- `_layouts/**`
- `assets/**`
- `about.md`
- `Gemfile`

For more information on this project, please visit: https://roadmap.sh/projects/github-actions-deployment-workflow
