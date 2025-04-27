# Weather FastMCP Server 

This project provides a **FastMCP server** exposing tools and resources to retrieve **real-time weather alerts**, perform **basic addition**, and handle **dynamic resource echoing**.  
It is designed for local development using **Model Context Protocol (MCP)**.

---

## 📂 Project Structure

| File | Purpose |
|:-----|:--------|
| `server/server.py` | FastMCP server for weather alerts, addition tool, and resources |
| `server/client.py` | Uses Airbnb Server and connects to an LLM for further tasks |

---

## 🚀 Setup and Run

Weather-Server
```
mcp dev server/server.py
```

Airbnb-Server
```
python server/client.py
```