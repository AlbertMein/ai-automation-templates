# ai-automation-templates

Starter templates and project scaffolds for common AI automation patterns.

## Templates

- **Agent starter** — Basic LangChain agent with tool use and memory
- **RAG pipeline** — Document loader + vector store + retriever + chain
- **API wrapper** — Provider-agnostic LLM client with retry and caching
- **Multi-agent crew** — CrewAI crew with roles, tasks, and tools
- **Data extraction** — Scraper + LLM extractor + Pydantic output schema
- **FastAPI service** — LLM-powered API endpoint with streaming support

## Stack

Each template uses:
- Python 3.10+
- pyproject.toml for packaging
- Pydantic for configuration
- pytest for testing
- ruff for formatting/linting
- .env.example for credentials

## Usage

Copy a template directory, rename it, and start building:

```bash
cp -r templates/agent-starter my-new-agent
cd my-new-agent
pip install -e .
```

## License

MIT
