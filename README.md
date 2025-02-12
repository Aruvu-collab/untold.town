# A custom theme for Untold.Town

This is a custom theme that has been built on top of the default theme `ease` from Ghost. This has been built with a templating language called handlebars that Ghost uses.

# Some quirks of Ghost and Handlebars

There are three major categories of contents which determines styling and templating. They are also determined by `routes.yaml` which makes collections and determines templates as well. This page will attempt to collect all of those quirks under one simple handbook

## Routing

### By post type

### By region

### Misc pages

## Content types

- page
- post

## Taxonomy

- tag
- post




# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev

# Build and upload to site
yarn zip
```
