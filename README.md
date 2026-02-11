# MCP DENO

## MCP Server Examples
### 1. MCP Server
```
docker run -it -p 81:8001 --rm  xxradar/mcp-hackbot:latest  bash
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
```
python mcp_server.py 
```
### 2. MCP Server Rogue
```
docker run -it -p 82:8002 --rm  xxradar/mcp-hackbot:latest  bash
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
```
python mcp_server_rogue.py 
```
### 3. DesktopCommander (Use with care !!)
```
docker run -it -p 80:8081 --rm  xxradar/mcp-hackbot:latest  bash
```
```
npx -y @wonderwhy-er/desktop-commander@latest setup
```
```
npx -y supergateway \
  --port 8081 \
  --outputTransport streamableHttp \
  --healthEndpoint /healthz \
  --stdio "npx -y @wonderwhy-er/desktop-commander@latest"
```

## Inspector
Inspector, a tool to interact with an MCP server
```
npx @modelcontextprotocol/inspector
```
