# Recipe Lighthouse Metrics

## Running Unlighthouse

Use [Unlighthouse](https://unlighthouse.dev/) to crawl the Recipe docs and gather recent [Lighthouse](https://github.com/GoogleChrome/lighthouse) metrics

1. `unlighthouse-ci --debug --build-static --output-path=./`

2. Before committing new metrics, add `<base href="https://ezcater.github.io/recipe-a11y/" />` to the `head` tag in `index.html`.
