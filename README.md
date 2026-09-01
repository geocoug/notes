# notes

[![ci/cd](https://github.com/geocoug/notes/actions/workflows/build-and-deploy.yml/badge.svg)](https://github.com/geocoug/notes/actions/workflows/build-and-deploy.yml)
[![website status](https://img.shields.io/website.svg?down_color=red&down_message=down&up_color=green&up_message=up&url=https%3A%2F%2Fnotes.geocoug.com)](https://notes.geocoug.com)

My personal notes - a collection of insights, resources, and inspirations that keep me productive and creative. You will find a wide array of content from development tips and code snippets to workout plans and recipes.

Published to [notes.geocoug.com](https://notes.geocoug.com) via GitHub Pages.

## Setup

1. Clone the repository: `git clone https://github.com/geocoug/notes.git`
2. Move into the cloned repository: `cd notes`
3. Install [uv](https://docs.astral.sh/uv/) and [Quarto](https://quarto.org/docs/get-started/)
4. Sync the Python environment: `uv sync --all-extras`
5. Install `pre-commit` hooks: `uv run pre-commit install --install-hooks`
6. Start the Quarto preview server: `uv run quarto preview`

## Quarto Extensions

- [black-formatter](https://github.com/shafayetShafee/black-formatter)
- [downloadthis](https://github.com/shafayetShafee/downloadthis)
- [fontawesome](https://github.com/quarto-ext/fontawesome)
- [interactive-sql](https://github.com/shafayetShafee/interactive-sql)
