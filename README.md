<h1 align="center">Richard Oyelowo</h1>

<p align="center">
  <strong>Backend engineer building async APIs, auth systems, and production backend tools.</strong>
</p>

<p align="center">
  Python · FastAPI · Flask · PostgreSQL · SQLAlchemy · Docker · CI/CD
</p>

---

### Engineering Focus

I build backend systems with clear service boundaries, integration tests, and explicit data access rules.

Current focus:

- Multi-tenant API design with organization, team, project, and task boundaries
- Authentication and authorization systems with JWT, OAuth2, bcrypt, and RBAC
- Async Python services with FastAPI, PostgreSQL, SQLAlchemy, Alembic, and pytest
- Developer tools that help engineers understand and improve codebases
- Expanding deeper into TypeScript, Go, and Rust

---

### Featured Projects

| Project | What it is | Stack |
|---|---|---|
| [gatevault](https://github.com/RichardOyelowo/gatevault) | Framework-agnostic Python auth library for JWT, bcrypt, OAuth2 login flow, and route protection | Python, JWT, bcrypt, OAuth2 |
| [Snip](https://github.com/RichardOyelowo/Snip) | FastAPI URL shortener with click tracking, admin tools, Docker, and PostgreSQL | FastAPI, PostgreSQL, SQLAlchemy, Docker |
| [clustra](https://github.com/RichardOyelowo/clustra) | Multi-tenant task management API with RBAC and strict organization/team/project isolation | FastAPI, PostgreSQL, async SQLAlchemy, Alembic |
| [chatforge.nvim](https://github.com/RichardOyelowo/chatforge.nvim) | Neovim plugin for interactive AI coding conversations inside the editor | Lua, Neovim |
| [Business-Dashboard](https://github.com/RichardOyelowo/Business-Dashboard) | Customer and order management system with role-based data access and email password reset | Flask, SQLAlchemy, SQLite/PostgreSQL |

---

### Open Source Package

[![PyPI](https://img.shields.io/pypi/v/richard-gatevault?style=flat-square)](https://pypi.org/project/richard-gatevault/)
[![Python](https://img.shields.io/pypi/pyversions/richard-gatevault?style=flat-square)](https://pypi.org/project/richard-gatevault/)
[![CI](https://img.shields.io/github/actions/workflow/status/RichardOyelowo/gatevault/ci.yml?style=flat-square)](https://github.com/RichardOyelowo/gatevault/actions)

```bash
pip install richard-gatevault
```

```python
from gatevault import TokenManager, GateVault

token_manager = TokenManager(secret_key="change-me")
gate = GateVault(token_manager=token_manager)
tokens = token_manager.create_tokens({"user_id": user.id})

@gate.protected
def get_profile(payload=None):
    return db.get_user(payload["user_id"])
```

---

### Current Build

I am designing **RepoLens**, a local-first codebase intelligence tool.

Goal:

```text
Map, score, and explain any repository so developers and AI agents can work safely inside it.
```

Planned scope:

- Repo health scoring
- Codebase maps
- Architecture checks
- Test and CI discovery
- Python, TypeScript, Go, and Rust adapters
- Agent readiness checks

---

### Links

- Portfolio: [richardoyelowo.github.io](https://richardoyelowo.github.io)
- PyPI: [richard-gatevault](https://pypi.org/project/richard-gatevault/)
- Live app: [Snip](https://snip-ly.xyz)
