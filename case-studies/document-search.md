# Document Search

## Context

A large shared document archive needed full-text search without replacing the entire document storage process. Users needed to find documents by content and metadata while respecting access rules and existing workflows.

## Work

- Designed and implemented a Java/Spring-based document indexing service.
- Used Apache Tika to extract full text and metadata from documents.
- Indexed data into Elasticsearch for fast full-text and fuzzy search.
- Built a web search prototype and client-side tooling for opening local results.
- Documented the project as a formal final project for professional training.

## Technologies

```text
Java · Spring Boot · Elasticsearch · Apache Tika · Thymeleaf
Gradle · Docker/Jib · GitLab CI/CD · Windows service · access-aware indexing
```

## Outcome

- Search over a large document set became available without a full document-management migration.
- The solution combined backend indexing, search UX, deployment, and operational documentation.
- The project remains a strong example of pragmatic system design under time and scope constraints.

[Back to case studies](README.md)

