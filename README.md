# FluidPhrases: Conversational AI with Distinct Personas

FluidPhrases is a system that generates natural conversations between two Language Learning Models (LLMs) with distinct personas. This repository contains notebooks and data sources for training and deploying the conversational AI system.

## Notebooks

### `h2oai.ipynb`

This notebook demonstrates how to:

- Upload documents into a collection and ingest them
- Create and upload prompt templates
- Get two collections to chat with each other

### `text_preprocessing.ipynb`

This notebook preprocesses the text data/transcripts for training the LLM personalities.

## Data Sources

The data used for training the LLM personalities is located in the `data` folder. Each persona has a dedicated subfolder containing the relevant text data or transcripts.

### `data/rapper`

- [Eminem Songs](https://www.kaggle.com/datasets/thaddeussegura/eminem-lyrics-from-all-albums)

### `data/educator`

- [TED Talks](https://www.kaggle.com/datasets/rounakbanik/ted-talks)

### `data/politician`

- [UN General Debates](https://www.kaggle.com/datasets/unitednations/un-general-debates)

### `data/comedian`

- [Stand-up Comedy Transcripts](https://scrapsfromtheloft.com/stand-up-comedy-scripts/)
- [Scraping Code](https://github.com/SethGo/ComedyNLP/blob/master/get_transcripts.ipynb)

### `data/L=lawyer`

- [Transcripts of Supreme Court Cases](https://github.com/EricWiener/supreme-court-cases)

### `data/philosopher`

- [Aristotle](http://classics.mit.edu/Browse/browse-Aristotle.html)
- [Plato](http://classics.mit.edu/Browse/browse-Plato.html)
- [Aeschylus](https://classics.mit.edu/Browse/browse-Aeschylus.html)
- [Epictetus](http://classics.mit.edu/Browse/browse-Epictetus.html)
