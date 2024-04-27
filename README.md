# Arxiv Vector Database

Using lancedb, we can convert arxiv abstracts to vector database.

There are two scripts to create and query a vector database. We need to install the following packages:

```
	pip install lancedb polars pyarrow sentence_transformers
```

1. Create a vector database:

```
	arxiv_createdb.ipynb
```

2. Query the data from vector database

```
	arxiv-querydb.ipynb
```
