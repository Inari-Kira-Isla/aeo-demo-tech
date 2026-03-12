# aeo-demo-tech

## Project
AEO Demo template for tech industry with Schema.org, llms.txt, FAQ, and AI-friendly markup. Built with HTML.

## Conventions
- Use semantic HTML5 elements
- Include proper meta tags for SEO and AI crawlers
- Add Schema.org structured data in JSON-LD
- Generate llms.txt for AI crawler compatibility
- Implement FAQPage schema markup
- Keep 2-space indentation for readability

## Naming
- Use lowercase with hyphens for file names (e.g., `tech-faq.html`)
- Use descriptive, SEO-friendly names matching content

## Architecture
- Single-page HTML templates
- Schema.org JSON-LD embedded in `<script type="application/ld+json">`
- Self-contained pages with inline styles when needed
- llms.txt alongside HTML files

## Commands
- No build commands required
- Deploy HTML files directly to any web server or CDN

## Do Not
- Don't use client-side frameworks (React, Vue, etc.)
- Don't omit Schema.org markup from content
- Don't minify HTML beyond readability
- Don't use server-side rendering for these templates
- Don't forget to include llms.txt for AI indexing