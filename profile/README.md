# Gully 

Gully is a sophisticated application that allows you to query a rich database of Indian Premier League (IPL) cricket statistics using plain English.

## Overview
Gully translates natural language queries into SQL, allowing you to explore ball-by-ball IPL data (2008-2025) without knowing any SQL. Ask questions like *"How many wides did Pathirana bowl in IPL 2024?"* and get instant answers.
## Repositories
| Repo | Description |
|------|-------------|
| [gully-core](https://github.com/The-Gully/gully-core) | AI agent that converts natural language to SQL queries, CLI tool, and FastAPI backend |
| [go-gully-backend](https://github.com/The-Gully/go-gully-backend) | Go-GIN REST API with Google OAuth authentication |

Under Developement
| Repo | Description |
|------|-------------|
| [gully-graph](https://github.com/Astrasv/gully-graph) | Graph + IPL cooking something amazing 😉 |

## Key Features
- **Natural Language Queries** — Ask complex questions about IPL history in plain English
- **Discord-like Tagging** — Use `@players`, `@teams`, `@venues`, `@umpires`, `@cities` for entity consistency
- **AI-Powered SQL Agent** — Dynamically generates precise SQL queries
- **OAuth Authentication** — Secure Google sign-in via the Go backend
- **Ball-by-Ball Data** — Comprehensive IPL dataset from 2008-2025


## Tech Stack
- **Core Agent**: Python, FastAPI, SQLAlchemy, Alembic, LLM agents
- **Backend**: Go, GIN framework, PostgreSQL, Google OAuth
- **Frontend**: React, Vite
- **Data**: PostgreSQL with ball-by-ball IPL data (2008-2025)
## License
MIT
