# AI-placement-prep-tracker
Minimal, runnable MVP for an AI-powered placement prep tracker.

**Scope (MVP)**  
- Store users (profile, skills, resume text) in SQLite.  
- Simple AI-like suggestion engine: keyword matching + lightweight TF-IDF similarity to job-role descriptions.  
- Single-process backend serving a tiny SPA (HTML+JS).  
- Dockerized, includes minimal tests.

---

## Repo structure
/ (root)
├─ Dockerfile
├─ requirements.txt
├─ .dockerignore
├─ pytest.ini
├─ README.md
├─ app/
│ ├─ main.py
│ ├─ db.py
│ ├─ models.py
│ ├─ crud.py
│ ├─ suggest.py
│ └─ static/
│ ├─ index.html
│ ├─ app.js
│ └─ styles.css
└─ tests/
└─ test_api.py
