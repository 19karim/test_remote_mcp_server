# Remote MCP Server

## Description
This project is a **FastMCP server** for tracking expenses and testing the MCP Inspector.
It allows you to add, list, and summarize expenses using a simple MCP interface.

Features include:
- Add new expense entries with date, amount, category, subcategory, and notes.
- List expenses within a date range.
- Summarize expenses by category over a specified period.
- Default and customizable categories stored in a JSON file.
- Asynchronous operations for better performance.

## Tech Stack
- Python 3.12
- FastMCP
- aiosqlite
- SQLite (database)
- Uvicorn (HTTP server)

## Setup Instructions
1. Clone the repository:
```bash
git clone https://github.com/19karim/test_remote_mcp_server.git
cd test_remote_mcp_server
```

2. Requirements:
```bash
uv init
uv install
uv run main.py
```
