# MCP DENO

## MCP Servers
```
docker run -it -p 80:8000 --rm  xxradar/mcp-hackbot:latest  bash
```
```
git clone https://github.com/xxradar/ftnt-demo-ai-mcp.git
```
```
python3 -m venv .venv
```
```
source .venv/bin/activate
```
```
cd ftnt-demo-ai-mcp/example/mcp
```
```
pip install -r requirements.txt
```
## MCP Server Examples
```
python mcp_server.py 
```
```
python mcp_server_rogue.py 
```
```
npx -y supergateway \
  --port 8080 \
  --outputTransport streamableHttp \
  --healthEndpoint /healthz \
  --stdio "npx -y @wonderwhy-er/desktop-commander@latest"
```

## Inspector
Inspector, a tool to interact with an MCP server
```
npx @modelcontextprotocol/inspector
```
