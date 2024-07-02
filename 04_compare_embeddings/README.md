# Compare embeddings

This notebook let's you run the same query against different embeddings to compare their outputs.

## Install requirements

To run the required vector database locally, use this command:
`docker run --name advanced-rag-04-compare-embeddings-demo-vectordb -p 6333:6333 -p 6334:6334 -d qdrant/qdrant`

Prepare the environment:
```
conda create --name advanced-rag-04-compare-embeddings python=3.9.5 -y
conda install --name advanced-rag-04-compare-embeddings pip==23.3 -y --force

conda env config vars set --name advanced-rag-04-compare-embeddings OPENAI_API_KEY={YOUR OPENAI API KEY}

conda activate advanced-rag-04-compare-embeddings
pip install -r requirements.txt
```

## Usage

Run the jupyter notebook.
