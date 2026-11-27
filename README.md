<div align="center">

<img src="https://nestdaddy.com/static/android-chrome-512x512.png" alt="NestDaddy" width="96">

# NestDaddy

> NestDaddy launched on Product Hunt on 17 Nov 2026. Feedback and reviews welcome: [producthunt.com/products/nestdaddy](https://www.producthunt.com/products/nestdaddy)

**An independent search engine with its own index.**
Web search, news and research data for apps and AI agents.

[Website](https://nestdaddy.com) · [Memory](https://nestdaddy.com/memory) · [API docs](https://nestdaddy.com/apis) · [MCP server](https://nestdaddy.com/mcp) · [Blog](https://nestdaddy.com/blog) · [X](https://x.com/nestdaddy_api) · [dev.to](https://dev.to/nestdaddy)

</div>

---

### What we build

| Product | What it does |
|---|---|
| **NestDaddy Search** | Web and news search from our own crawler and index, not a wrapper around another engine. |
| **Search & News API** | Plain JSON for web search, news by key words, topic and country, the readable text of any page, and research papers. |
| **NestDaddy Memory** | If you want your AI projects to perform, you need memory. One memory for every AI you use: tell it once, and every AI you connect remembers it tomorrow, on every device. Any MCP app, any model. 7 days free, then $9.99 a month. [nestdaddy-memory](https://github.com/nestdaddy-ai/nestdaddy-memory) · [nestdaddy.com/memory](https://nestdaddy.com/memory). Listed as `com.nestdaddy/memory`. |
| **NestDaddy MCP** | One remote MCP server that gives Claude, Cursor, VS Code, n8n and any MCP client live search and news. Listed in the [Official MCP Registry](https://registry.modelcontextprotocol.io) as `com.nestdaddy/nestdaddy` and on [Glama](https://glama.ai/mcp/connectors/com.nestdaddy/nestdaddy). [![NestDaddy MCP connector](https://glama.ai/mcp/connectors/com.nestdaddy/nestdaddy/badges/score.svg)](https://glama.ai/mcp/connectors/com.nestdaddy/nestdaddy) |

### Open source examples

| Repository | |
|---|---|
| [nestdaddy-memory](https://github.com/nestdaddy-ai/nestdaddy-memory) | Connect NestDaddy Memory to any MCP app: ChatGPT, Claude, Cursor, VS Code and more |
| [nestdaddy-examples](https://github.com/nestdaddy-ai/nestdaddy-examples) | Python, JavaScript, curl and MCP examples for every endpoint |
| [ollama-web-search](https://github.com/nestdaddy-ai/ollama-web-search) | Give a local LLM (Ollama) live web search, news and page reading |
| [news-digest-bot](https://github.com/nestdaddy-ai/news-digest-bot) | A daily news digest to Telegram, Slack or email |

### Start building

```bash
curl "https://nestdaddy.com/api/v1/search?q=model+context+protocol" -H "X-API-Key: YOUR_KEY"
```

There is a 7-day free trial: **[get a key](https://nestdaddy.com/pricing)**.

<sub>Building with NestDaddy? Our [affiliate programme](https://nestdaddy.com/affiliates) pays 30% for life.</sub>

Building AI agents? Join our community, **Agent Builders**, on [Discord](https://discord.gg/CXStfSFC3v).
