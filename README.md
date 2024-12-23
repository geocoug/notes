# toolkit

[![ci/cd](https://github.com/geocoug/toolkit/actions/workflows/build-and-deploy.yml/badge.svg)](https://github.com/geocoug/toolkit/actions/workflows/build-and-deploy.yml)
[![website status](https://img.shields.io/website.svg?down_color=red&down_message=down&up_color=green&up_message=up&url=http%3A%2F%2Ftoolkit.geocoug.com)](https://toolkit.geocoug.com)

This site is my personal toolkit - a collection of insights, resources, and inspirations that keep me productive and creative. You will find a wide array of content from development tips and code snippets to workout plans and recipes.

## Setup

1. Clone the repository: `git clone https://github.com/geocoug/toolkit.git`
2. Move into the cloned repository: `cd toolkit`
3. Create a Python virtual environment and activate it
   1. **Windows**: `python3 -m venv .venv; .\.venv\Scripts\activate`
   2. **Linux/MacOS**: `python3 -m venv .venv && source ./.venv/bin/activate`
4. Install the Python requirements: `python -m pip install -r requirements.txt`
5. Install `pre-commit` hooks: `python -m pre_commit install --install-hooks`
6. Start the Quarto preview server: `quarto preview`

## Using the Jupyter Notebooks

Jupyter Lab can be spun up to using the [docker-compose.yml](./docker-compose.yml) file with `docker compose up -d`. The notebook directory (`development/code/notebooks`) gets bind mounted into the docker container. The notebook environment is served locally at [http://jupyter.localhost](http://jupyter.localhost) using [Caddy](https://caddyserver.com/).

## Quarto Extensions

- [black-formatter](https://github.com/shafayetShafee/black-formatter)
- [downloadthis](https://github.com/shafayetShafee/downloadthis)
- [fontawesome](https://github.com/quarto-ext/fontawesome)
- [interactive-sql](https://github.com/shafayetShafee/interactive-sql)
