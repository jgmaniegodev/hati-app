---
paths:
  - "tests/**/*.py"
---

# Rules for tests/**/*.py

- Every test has one clear assertion about behaviour
- Put shared fixtures in tests/conftest.py (create it if it doesn't exist yet), don't create new database setups
- Name tests test_<what>_<when>_<expected>
