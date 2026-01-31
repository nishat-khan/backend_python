# backend_python
Backend in a Python based API framework


Code Stack:<br>
Python3.11: Most stable for libraries below<br>
FastAPI: API framework in Python<br>
Uvicorn: ASGI server for FastAPIs<br>
Pydantic(v2): Schema validation<br>
SQLAlchemy: data access layer<br>
SQLite: DB engine (sqlite3 is inbuilt in Python3.11)<br>
Redis: Caching<br>
Pytest: Unit tests<br>


To install the virtual environment:
`cd path/to/backend_python`
`python3.11 -m venv .venv`
`source .venv/bin/activate`
`pip install -r requirements.txt`

If you get any issues with pip installs, try cleaning pip's cache first
`pip cache purge`
