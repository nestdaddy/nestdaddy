<div align="center">

<img src="https://nestdaddy.com/static/android-chrome-512x512.png" alt="NestDaddy" width="96">

# NestDaddy

**An independent search engine with its own index.**
Web search, news and research data for apps and AI agents.

[Website](https://nestdaddy.com) · [API docs](https://nestdaddy.com/apis) · [MCP server](https://nestdaddy.com/mcp) · [Blog](https://nestdaddy.com/blog) · [X](https://x.com/nestdaddy_api) · [dev.to](https://dev.to/nestdaddy)

</div>

---

### What we build

| Product | What it does |
|---|---|
| **NestDaddy Search** | Web and news search from our own crawler and index, not a wrapper around another engine. |
| **Search & News API** | Plain JSON for web search, news by key words, topic and country, the readable text of any page, and research papers. |
| **NestDaddy MCP** | One remote MCP server that gives Claude, Cursor, VS Code, n8n and any MCP client live search and news. Listed in the [Official MCP Registry](https://registry.modelcontextprotocol.io) as `com.nestdaddy/nestdaddy`. |

### Open source examples

| Repository | |
|---|---|
| [nestdaddy-examples](https://github.com/nestdaddy/nestdaddy-examples) | Python, JavaScript, curl and MCP examples for every endpoint |
| [ollama-web-search](https://github.com/nestdaddy/ollama-web-search) | Give a local LLM (Ollama) live web search, news and page reading |
| [news-digest-bot](https://github.com/nestdaddy/news-digest-bot) | A daily news digest to Telegram, Slack or email |

### Start building

```bash
curl "https://nestdaddy.com/api/v1/search?q=model+context+protocol" -H "X-API-Key: YOUR_KEY"
```

Free plan with 1,000 calls every month, no card: **[get a key](https://nestdaddy.com/apis)**.

<sub>Building with NestDaddy? Our [affiliate programme](https://nestdaddy.com/affiliates) pays 30% for life.</sub>

Building AI agents? Join our community, **Agent Builders**, on [Discord](https://discord.gg/CXStfSFC3v).
