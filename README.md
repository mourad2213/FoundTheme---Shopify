# Shopify Theme - Found
A clean Shopify Online Store 2.0 theme built with Liquid and Tailwind CSS. This repository contains the theme source along with the compiled assets in `assets/`.

## Requirements

- Shopify CLI
- Node.js (for Tailwind build)

## Project Structure

- `assets/` - compiled CSS/JS and theme assets
- `config/` - theme settings and schema
- `layout/` - theme layout files
- `locales/` - translations
- `sections/` - reusable theme sections
- `snippets/` - partial templates
- `src/` - Tailwind source styles
- `templates/` - page templates

## Getting Started

Clone the repository and install dependencies:

```sh
npm install
```

## Development

Compile Tailwind CSS once:

```sh
npx @tailwindcss/cli -i ./src/tailwind.css -o ./assets/application.css
```

Watch for changes:

```sh
npx @tailwindcss/cli -i ./src/tailwind.css -o ./assets/application.css --watch
```

## Shopify CLI

Start a local theme preview:

```sh
shopify theme dev
```

## Notes

- Edit Liquid files in `sections/`, `snippets/`, and `templates/`.
- Update Tailwind styles in `src/tailwind.css`, then rebuild `assets/application.css`.
