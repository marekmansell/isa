# ISA Mini-project 1: Collaborative Filtering on Goodreads Poetry

## Data

Download the Goodreads Poetry subset from [UCSD Goodreads Datasets](https://cseweb.ucsd.edu/~jmcauley/datasets/goodreads.html#datasets) and place the files in `data/`:

```
data/
  goodreads_books_poetry.json.gz
  goodreads_interactions_poetry.json.gz
  goodreads_reviews_poetry.json.gz
```

## Setup & Run

```bash
uv sync
uv run jupyter notebook notebook.ipynb
```
