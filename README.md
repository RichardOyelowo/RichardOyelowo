# Richard Oyelowo

**Backend engineer building async APIs, auth systems, and production backend tools.**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI/CD-2088FF?style=flat&logo=githubactions&logoColor=white)

📍 Open to remote backend and AI engineering roles.

---

### Engineering Focus

I build backend systems with clear service boundaries, integration tests, and explicit data access rules.

Current focus:

- Multi-tenant API design with organization, team, project, and task boundaries
- Authentication and authorization systems with JWT, OAuth2, bcrypt, and RBAC
- Async Python services with FastAPI, PostgreSQL, SQLAlchemy, Alembic, and pytest
- Data structures and algorithms in C, the fundamentals layer under everything else
- Developer tools that help engineers understand and improve codebases

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

### Links

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://richardoyelowo.github.io)
[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/richard-gatevault/)
[![Snip](https://img.shields.io/badge/Live_App_Snip-4B32C3?style=for-the-badge&logo=link&logoColor=white)](https://snip-ly.xyz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/richard-oyelowo)
