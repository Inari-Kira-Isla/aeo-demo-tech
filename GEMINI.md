# aeo-demo-tech

## Overview
A technical industry template designed for AEO (Answer Engine Optimization). It demonstrates best practices for creating AI-friendly web pages by combining semantic HTML, structured data (Schema.org), and specific AI discovery files like `llms.txt`.

## Tech Stack
- **Core:** HTML5
- **Data:** JSON-LD (Schema.org)
- **AI Discovery:** llms.txt
- **Components:** FAQ (Details/Summary pattern)

## Architecture
- `index.html`: Core template containing semantic content, FAQ sections, and Schema.org JSON-LD scripts.
- `llms.txt`: A text-based sitemap specifically formatted for Large Language Models (LLMs) to ingest content structure.
- `assets/`: Contains CSS and minimal JS required for the template.

## Commands
- **Local Preview:** Serve the directory using a static server (e.g., `python3 -m http.server` or `npx serve`) to ensure relative paths and `llms.txt` are accessible.
- **Validation:** Use Google's Rich Results Test or Schema Markup Validator to verify the JSON-LD implementation.
- **Linting:** Ensure HTML is semantic and valid using the W3C Validator.

## Coding Style
- Use **Semantic HTML5** elements (`<main>`, `<article>`, `<section>`, `<h1>`-`<h6>`) to aid AI parsing.
- Place JSON-LD in the `<head>` or footer; do not inline in body text.
- Structure FAQ using `<details>` and `<summary>` for accessibility, or structured list items for strict Schema support.
- Keep the `llms.txt` file synced with the main content.

## Important Rules
- **Schema.org is Mandatory:** Every page must include relevant JSON-LD for SEO.
- **AI Accessibility:** Avoid blocking content with CAPTCHAs or heavy client-side rendering. Content must be readable by bots.
- **No Placeholder Data:** Content should be realistic to demonstrate the "Tech" industry context effectively.