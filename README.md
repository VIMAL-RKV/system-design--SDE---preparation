# System Design – SDE-1 Preparation

A step-by-step learning repository for System Design fundamentals, interview preparation, revision notes, and interactive architecture simulations.

## Learning rules

- Study one topic at a time.
- For each topic, keep a concise explanation, an architecture diagram, real-world examples, failure scenarios, Java/Spring Boot connections, and interview questions.
- Keep the interactive simulation alongside the topic's notes.
- Add a topic only after completing the lesson and checking the revision notes.

## Completed topics

| # | Topic | Status | Notes | Simulation |
|---|---|---|---|---|
| 01 | Client–Server Architecture | Foundation completed | [Word notes](topics/01-client-server-architecture/Client_Server_Architecture_Notes.docx) | [Open simulation](docs/topics/01-client-server/index.html) |

## Planned topics

1. HTTP, HTTPS, REST API and DNS
2. Database fundamentals
3. Load balancing
4. Caching
5. Database scaling: replication and sharding
6. Message queues and Kafka
7. Core system concepts: scaling, latency, throughput, availability, reliability, fault tolerance and CAP theorem

## Repository structure

```text
system-design-sde1/
├── README.md
├── GITHUB_SETUP.md
├── topics/
│   └── 01-client-server-architecture/
│       └── Client_Server_Architecture_Notes.docx
├── docs/
│   ├── index.html
│   └── topics/
│       └── 01-client-server/
│           └── index.html
└── templates/
    └── topic-template.md
```

- `topics/` contains learning notes and supporting files.
- `docs/` contains browser-openable simulations and the GitHub Pages landing page.
- `templates/` contains the repeatable structure for future topics.

## Add the next topic

Copy [`templates/topic-template.md`](templates/topic-template.md), create a numbered folder under `topics/`, add the completed Word notes, and add its simulation under `docs/topics/<topic-slug>/index.html`. Then update the completed-topics table above.
