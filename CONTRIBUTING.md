## Setting up for local development

1. [Install Quarto](https://quarto.org/docs/get-started/)
   - Can use [Homebrew](https://formulae.brew.sh/cask/quarto#default) if you want with `brew install quarto`
2. Install Python if you don't already have it

more
srtdsrtd
## Rendering Locally

1. Run `quarto preview`

## Publishing

When done developing and are ready to publish, run the
following [^1].

1. `quarto publish gh-pages`

[^1]: [Quarto docs](https://quarto.org/docs/publishing/github-pages.html#publishing)

## Branching Structure

The `main` branch is what we use for our work.
The `gh-pages` branch we don't touch manually -- it
gets written to when we run the publish command mentioned
above.

stuff
here