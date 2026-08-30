# Aditya C Shekhar

## Backend Engineer | Java, Spring Boot & Distributed Systems

I build backend systems and APIs, with a focus on the parts that determine how they behave in practice: data modeling, persistence, caching, asynchronous work, service boundaries, and failure handling.

My primary stack is Java and Spring Boot. I also use Python and FastAPI for backend tooling and AI applications, and I am currently deepening my understanding of distributed systems, event-driven architecture, and retrieval-augmented generation.

## Selected Work

### [MinSearch](https://github.com/AdityaCShekhar/MinSearch)

Java and Spring Boot document-search system organized as a multi-module repository.

- Auth, document, and search service boundaries
- PostgreSQL persistence with Docker-based local infrastructure
- Redis and Kafka integration boundaries for caching and asynchronous processing
- Custom indexing/search work, API contracts, and Testcontainers-oriented verification

### [CodeSmith](https://github.com/AdityaCShekhar/CodeSmith)

Repository-aware Python coding assistant built around an agent runtime.

- OpenRouter model integration and tool calling
- Context injection for repository files
- Permission-aware file operations and command execution
- Docker support, CLI workflows, and tests for agent behavior

### [Toxicity-Detection](https://github.com/AdityaCShekhar/Toxicity-Detection)

Production-oriented local text-moderation platform combining a Flask inference API with a Chrome Manifest V3 extension.

- TensorFlow/Keras inference with a persisted vocabulary and configurable threshold
- Single-text and batched classification endpoints with input limits and validation
- Docker and Gunicorn deployment with health checks and OpenAPI documentation
- Structured request logging, response timing, model evaluation tooling, unit tests, and CI coverage

The extension scans page text, batches requests to the local API, and blurs content classified as toxic. This is an AI/API project that complements my backend focus.

## Technical Focus

| Area | Tools and concepts |
| --- | --- |
| Backend | Java, Spring Boot, Spring Security, JPA/Hibernate, Python, FastAPI, REST APIs |
| Data | PostgreSQL, SQL, Redis, database design, indexing, caching |
| Distributed systems | Kafka, event-driven architecture, asynchronous processing, service boundaries, system design |
| AI applications | RAG, embeddings, semantic search, FAISS, Sentence Transformers, LLM APIs |
| Delivery | Docker, Git, GitHub Actions, Linux |

## Current Direction

- Designing and implementing backend services with Spring Boot
- Learning distributed-systems fundamentals through messaging, caching, consistency, and failure modes
- Exploring PostgreSQL internals, search indexing, and performance trade-offs
- Building small AI-backed services with FastAPI, embeddings, vector search, and RAG patterns

## Contact

[GitHub](https://github.com/AdityaCShekhar)
