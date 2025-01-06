# Question Answering Challenge (PolEval 2021)

## Set up

#### Install dependencies

```bash
python3 -m venv .venv
source ".venv/bin/activate"
pip install -r requirements.txt
```

#### Run Elasticsearch locally

Make sure you have Docker installed. Run the following command in your terminal to set up a single-node local cluster in Docker:

```bash
docker-compose up
```

#### Download the Wikipedia Dump

Run the `Using a Wikipedia dump for offline retrieval` section.

#### Run WikiExtractor

```bash
wikiextractor --json plwiki-latest-pages-articles.xml.bz2 -o extracted
```

#### Run the rest of the steps
