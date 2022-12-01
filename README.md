# Recipe Lighthouse Metrics

## Running Unlighthouse

Use [Unlighthouse](https://unlighthouse.dev/) to crawl the Recipe docs and gather recent [Lighthouse](https://github.com/GoogleChrome/lighthouse) metrics

## If you don't have unlighthouse and puppeteer installed:

`npm install -g @unlighthouse/cli puppeteer`

## First, in the `/web` directory, run unlighthouse on desktop:

`unlighthouse-ci --debug --build-static --output-path=./`

## Second, in the `/mobile` directory, run unlighthouse on mobile:

`unlighthouse-ci --debug --build-static --output-path=./`

## Publish:

Make a PR, get a code review, and merge.
