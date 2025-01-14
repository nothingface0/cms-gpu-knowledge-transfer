# cms-gpu-knowledge-transfer

Documentation will be available at: [https://nothingface0.github.io/cms-gpu-knowledge-transfer/](https://nothingface0.github.io/cms-gpu-knowledge-transfer/)

## Developing locally

- Create a python venv: `python3 -m venv venv`
- Activate it: `source venv/bin/activate`
- Install requirements: `pip install -U -r requirements.txt`
- Run `mkdocs serve` from the root repo directory.

## Deploy latest version to GitHub Pages

- Activate the project's venv
- Run: `mkdocs gh-deploy`

## GitHub configuration

Navigate to `Settings` -> `Pages`:

- Select the `gh-pages` branch which is automatically created by `mkdocs`.
- Select the `/ (root)` directory.
- Click `Save`.
