# Stochastic Learning Ascent

Click [**Use this template**](https://github.com/dieghernan/chulapa-101/generate) button above for cloning this repo and get started with [Chulapa Jekyll theme](https://github.com/dieghernan/chulapa).

Contains basic configuration to get you a site with:

- [Sample posts](./_posts/) and [paginated blog index](./blog/index.html).
- Archive pages for posts grouped by year, category, and tag.
- Demo page with the different Bootstrap components and how they look with the actual skin settings.
- Sample 404 page.
- Site search with Lunr.
- Sample [`_config`](_config.yml) with minimal configuration.
- Sample [`algolia-search.yml`](algolia-search.yml) for using Algolia+GitHub Actions. More guidance in the top of the file.
- Sample files for extending the theme with your [own scripts](./_includes/custom/) and [css](./assets/css/).

[Configure as necessary](https://dieghernan.github.io/chulapa/docs/02-config) and replace sample content with your own.

## Original Repository
Repository: [Chulapa Github](https://github.com/dieghernan/chulapa)

## Demo Page
Demo: [here](https://jamstackthemes.dev/demo/theme/chulapa/)

## Theme Documentation
Theme documentation can be found at: [Chulapa Theme](https://dieghernan.github.io/chulapa/docs/).

## Setup
To build use:
```
bundle build
```

To test locally use:
```
bundle exec jekyll serve --livereload --incremental
```

To remove all generated files use:
```
bundle clean
```