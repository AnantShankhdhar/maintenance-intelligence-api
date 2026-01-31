# Industrial Maintenance Intelligence API

Transform unstructured maintenance documents into decision-ready reliability intelligence.

> "Factories don't lack maintenance data — they lack the ability to learn from it."

## Quick Start

```bash
git clone https://github.com/AnantShankhdhar/maintenance-intelligence-api.git
cd maintenance-intelligence-api
docker-compose up -d
```

## Features

- **AI Extraction**: Claude Sonnet parses unstructured documents
- **Vector Search**: OpenAI embeddings for semantic similarity
- **Failure Analytics**: Track patterns and recurring issues
- **Cost Optimization**: Caching, batching, smart filtering

## API Endpoints

- `POST /documents/upload` - Upload documents
- `POST /failures/search` - Semantic search for similar failures
- `GET /failures/analytics/summary` - Failure analytics
- `GET /equipment/{id}/stats` - Equipment reliability stats

## Tech Stack

- FastAPI + PostgreSQL + pgvector
- Claude Sonnet (Anthropic) + OpenAI Embeddings
- Docker for deployment

## License

MIT