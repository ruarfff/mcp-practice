# mcp-practice

Following along with the course <https://learn.deeplearning.ai/courses/mcp-build-rich-context-ai-apps-with-anthropic/>

## Setup

Have node and python installed.

Install uv.

```bash
uv sync
```

## Setup API Key

Need an anthropic account. Create a key at <https://console.anthropic.com/settings/keys>

Update ./.env with your API key:

```
ANTHROPIC_API_KEY=your_api_key_here
```

## Run Sever

```bash
npx @modelcontextprotocol/inspector uv run src/server.py
```
