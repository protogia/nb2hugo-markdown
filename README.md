# nb2hugo-markdown
Utility to convert jupyter-notebooks into hugo-renderable markdowns supporting outputs from plotly and matplotlib.

## install
```bash
poetry shell
poetry install
```

## run
```bash
poetry run python src/__main__.py --file /path/to/notebook/your-nb.ipynb --destination /path/to/hugo/blog/content/your-nb.md
# will create also the source folders and put necessary files into it:
# - /path/to/hugo/blog/static/plotly/your-nb/
# - /path/to/hugo/blog/static/img/your-nb/
```
