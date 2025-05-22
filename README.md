## Build App FastAPI with MCP

### Guide

```bash
python -m venv .venv
```

For Windows, bisa pakai Git Bash,

```bash
source .venv/Scripts/activate
```

For Mac,

```bash
source .venv/bin/activate
```

```bash
pip install "fastapi[standard]"
```

```bash
pip install crawl4ai
```
```bash
crawl4ai-setup
```
```bash
crawl4ai-doctor
```

```bash
pip freeze > requirements.txt
```

Jika sudah ada ada file requirements.txt, kita bisa menjalankan perintah ini,

```bash
pip install -r requirements.txt
```

### Source

- [FastAPI-MCP](https://fastapi-mcp.tadata.com/getting-started/welcome)
- [Crawl4AI](https://docs.crawl4ai.com/)