<div align="center">

<img src="assets/logo.png" alt="Legal AI Platform Logo" width="140">

# Legal AI Platform

### Docker Compose deployment stack for a legal AI API backend and Redis state cache.

[![License](https://img.shields.io/badge/License-MIT-green?style=flat)](LICENSE) ![Stack](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

[Documentation](docker-compose.yml) · [Repository](https://github.com/bsdkijc-dev/legal-ai-platform)

</div>

---

Docker Compose setup for a legal AI API backend (`api_backend`, port 8000) and a Redis state cache (`state_cache_db`).

## Setup

1. Copy `.env.example` to `.env`.
2. Set `VALID_SECRET_TOKEN` and `REDIS_PASSWORD` in `.env`. Docker Compose will not start without them.
3. Run `docker compose up -d`.

`.env` is git-ignored. Never commit real secrets.

The `sample_data/` and `.config/` folders came from a Google Colab session; they are not part of the platform.

## Author and citation

**Author:** Cecep Mustafa, Indonesian Judicial College (IJC). ORCID: [0000-0003-0037-497X](https://orcid.org/0000-0003-0037-497X)

**Cite as:** Mustafa, C. (2026). *Legal AI Platform (deployment configuration)* [Computer software]. GitHub. https://github.com/bsdkijc-dev/legal-ai-platform

GitHub also shows a "Cite this repository" button, built from `CITATION.cff`.

## Licence

MIT (code and configuration). See `LICENSE`.

---

<div align="center">

**Legal AI Platform**

[github.com/bsdkijc-dev/legal-ai-platform](https://github.com/bsdkijc-dev/legal-ai-platform)

</div>
