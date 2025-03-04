# Copilot Instructions for Website Generation

This file provides guidelines for GitHub Copilot when assisting with the Torres Classics website development.

## Project Overview

Torres Classics is a website showcasing classical content. The site is built using Jekyll and hosted on GitHub Pages.

## Site Structure

- `_data/`: Contains YAML/JSON data files that the site uses
- `_includes/`: Partial templates
- `_layouts/`: Page layout templates
- `_posts/`: Blog posts (dated YYYY-MM-DD-title.md)
- `_pages/`: Static pages
- `assets/`: Images, CSS, and JavaScript files

## Conventions

- Use Markdown for content files
- Follow Jekyll front matter conventions

    ```yaml
    ---
    layout: post
    title: "Post Title"
    date: YYYY-MM-DD
    categories: [category1, category2]
    ---
    ```

- Use semantic HTML in templates
- CSS follows BEM methodology
- JavaScript is vanilla or minimal dependencies

## Common Tasks

- Creating new blog posts
- Updating page layouts
- Modifying site navigation
- Handling responsive design issues
- Optimizing images and assets
- Improving SEO elements

## Development Setup

When suggesting code, optimize for Jekyll best practices and static site performance.

## Content Guidelines

- Formal, academic tone for classical content
- SEO-friendly headings and metadata
- Accessible markup practices
- Consistent image formatting and captions
- Clear, concise writing style

## Functionality

- Responsive design for mobile and desktop
- SEO optimization for search engines
- Accessibility features for screen readers
- Performance optimization for fast loading
- Social media integration for sharing
- Image galleries for showcasing projects
