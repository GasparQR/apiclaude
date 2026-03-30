# altatech-api

Proxy serverless para conectar AltatechCRM con la API de Anthropic.

## Setup

1. Subí este repo a GitHub
2. Importalo en Vercel (vercel.com/new)
3. En Vercel → Settings → Environment Variables, agregá:
   - Name: `ANTHROPIC_API_KEY`
   - Value: `sk-ant-...` (tu key de Anthropic)
4. Deploy

## Endpoint

`POST /api/claude`

Body:
```json
{
  "messages": [{ "role": "user", "content": "tu prompt" }]
}
```
