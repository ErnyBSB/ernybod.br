# ernybod.br

Production website built with [Quarto](https://quarto.org).

## Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) installed on your system

## Local Development

To preview the website locally:

```bash
quarto preview
```

This will start a local server and open the website in your browser. The preview will automatically reload when you make changes to the source files.

## Building the Site

To render the website:

```bash
quarto render
```

The rendered site will be available in the `_site/` directory.

## Project Structure

- `_quarto.yml` - Main Quarto configuration file
- `index.qmd` - Home page
- `about.qmd` - About page
- `styles.css` - Custom CSS styles
- `.gitignore` - Git ignore patterns for Quarto projects

## Adding New Pages

1. Create a new `.qmd` file in the root directory
2. Add YAML frontmatter with a title
3. Add the page to the navbar in `_quarto.yml` if needed

## Customization

- Edit `_quarto.yml` to modify site configuration, theme, or navigation
- Modify `styles.css` to customize the appearance
- Update content in `.qmd` files using Markdown and Quarto features

## Learn More

- [Quarto Documentation](https://quarto.org/docs/guide/)
- [Quarto Websites Guide](https://quarto.org/docs/websites/)
