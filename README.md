# MSRD: Movie Search Ranking Dataset

This dataset is a MovieLens/TMDB-based crowd-sourced training data for search relevance models. It has:
* Movie metadata from TMDB/Movielens: title, description, actors, genres, characters, tags, dates, budget, votes.
* 28320 movie related search queries collected with Google Keyword Planner.
* User metadata: mobile/desktop platform and number of columns in the UI.
* 667k relevance labels made by ~1000 people, with corresponding BM25 scores.

Dataset is built using [toloka.ai](https://toloka.ai) platform with real humans and contains no synthetic data.

## Data and tools

* the actual dataset is located in the [dataset](https://github.com/metarank/msrd/tree/master/dataset) directory.
* `movies.csv` is a tab-delimited movie metadata, with TMDB movie ids.
* `queries.csv` is a tab-delimited relevance judgements.

Source data is anonymized and contains only abstract random user identifiers.

## License

* the dataset is shared under the [CC-BY-SA 4.0 license](LICENSE.md)