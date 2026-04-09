<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Backend+Engineer+%7C+Python+%7C+FastAPI+%7C+Systems+Design;Authentication+Systems+%7C+Multi-Tenant+Architecture;Async+APIs+%7C+PostgreSQL+%7C+Docker&font=Fira%20Code&center=true&width=680&height=50&color=3776AB&pause=1000">
</p>

<h1 align="center">Richard Oyelowo</h1>

<p align="center">
  <strong>Backend Engineer (Python · FastAPI · Systems Design)</strong><br/>
  <sub>Designing authentication systems, multi-tenant architectures, and scalable backend services</sub>
</p>

---

### 📌 Engineering Focus

Backend engineer specializing in authentication systems, multi-tenant architecture, and async backend services.  
Progressed from Flask-based REST APIs to FastAPI-based scalable systems with Docker, CI/CD, and production deployments.

### 🛠️ Stack

<p align="left">
<a href="https://www.python.org/"><img src="https://img.icons8.com/color/48/python.png" width="36" title="Python"/></a>
<a href="https://fastapi.tiangolo.com/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="36" title="FastAPI"/></a>
<a href="https://flask.palletsprojects.com/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" width="36" title="Flask"/></a>
<a href="https://www.postgresql.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="36" title="PostgreSQL"/></a>
<a href="https://www.docker.com/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="36" title="Docker"/></a>
<a href="https://git-scm.com/"><img src="https://img.icons8.com/color/48/git.png" width="36" title="Git"/></a>
<a href="https://www.linux.org/"><img src="https://img.icons8.com/color/48/linux.png" width="36" title="Linux"/></a>
<a href="https://www.sqlalchemy.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlalchemy/sqlalchemy-original.svg" width="36" title="SQLAlchemy"/></a>
<a href="https://redis.io/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="36" title="Redis"/></a>
<a href="https://github.com/features/actions"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="36" title="GitHub Actions"/></a>
</p>

---

### 📦 Open Source

<table>
<tr>
<td width="60%">

**[gatevault](https://github.com/RichardOyelowo/gatevault)**

Authentication and authorization library for Python applications implementing JWT-based authentication, OAuth2 flows, bcrypt password hashing, and RBAC permission control.

**Stack:** Python · JWT · OAuth2 · bcrypt · FastAPI/Flask compatible design

[![PyPI](https://img.shields.io/pypi/v/richard-gatevault?style=flat-square)](https://pypi.org/project/richard-gatevault)
[![Python](https://img.shields.io/pypi/pyversions/richard-gatevault?style=flat-square)](https://pypi.org/project/richard-gatevault)
[![CI](https://img.shields.io/github/actions/workflow/status/RichardOyelowo/gatevault/ci.yml?style=flat-square)](https://github.com/RichardOyelowo/gatevault/actions)

</td>

<td width="40%" align="center">

```python
@gate.protected
def get_profile(payload=None):
    return db.get_user(payload["user_id"])
