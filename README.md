# PiSearch

A minimal **Google search web UI** — type a query, get formatted result links. Flask frontend over the `googlesearch` Python library.

![Flask](https://img.shields.io/badge/Flask-Python-000000?style=flat-square&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)

## Features

- Clean search form → results page flow
- `GET /search?search=...` endpoint
- Helper module for query formatting
- Static assets + icons for a polished UI shell

## Tech stack

- **Flask**
- **googlesearch** (Google search results library)
- **Jinja2** templates

## Quick start

```bash
pip install flask google
python app.py
```

Visit **http://127.0.0.1:5000** and search.

## Project layout

```
app.py
helpers.py
templates/
static/
icons/
```

## Notes

Respect Google's terms of service and rate limits. For production, use the official Custom Search API.

---

[malimba](https://github.com/malimba)
