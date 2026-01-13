# ernybod.br
production web site

## About

This is a website built with [Quarto](https://quarto.org), an open-source scientific and technical publishing system.

## Getting Started

### Prerequisites

- Install Quarto from [quarto.org](https://quarto.org/docs/get-started/)

### Building the Site

To preview the site locally:

```bash
quarto preview
```

To build the site:

```bash
quarto render
```

The rendered site will be in the `_site` directory.

## Project Structure

- `_quarto.yml` - Main Quarto configuration file
- `index.qmd` - Home page
- `about.qmd` - About page
- `styles.css` - Custom CSS styles
- `_site/` - Generated site output (excluded from git)
