# Vector Embedding Pipeline

High-throughput vector embedding pipeline processing 237M+ biomedical text spans using Amazon Titan Embeddings with distributed batch processing.

## Architecture

```
vector-embedding-pipeline/
  src/           # Core modules
  tests/         # Unit and integration tests
  config/        # Configuration files
  docs/          # Documentation
```

## Modules

- **chunk_tokenizer**: Core chunk tokenizer functionality
- **embedding_client**: Core embedding client functionality
- **batch_processor**: Core batch processor functionality
- **index_builder**: Core index builder functionality
- **similarity_search**: Core similarity search functionality

## Quick Start

```bash
pip install -r requirements.txt
python -m vector_embedding_pipeline.main
```

## Testing

```bash
pytest tests/ -v
```

## License

MIT License - see LICENSE for details.
