# csound-plugins.github.io

Source of the Csound Plugins website, built with [MkDocs](https://www.mkdocs.org/)
and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.
The rendered site is published to <https://csound-plugins.github.io/>.

## Local development

```sh
python -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

## Publishing

Any push to `main` triggers the `build-site` workflow, which builds the site
with MkDocs and deploys it through GitHub Pages.
