# Instalação detalhada

INMETRO Instrumentos: Veículos Tanque é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_inmetro_instrumentos_vc_tanque`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_inmetro_instrumentos_vc_tanque` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_inmetro_instrumentos_vc_tanque` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_inmetro_instrumentos_vc_tanque` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.inmetro_instrumentos_vc_tanque` (ou `servers.inmetro_instrumentos_vc_tanque` no VS Code) do config do cliente e reinicie.
