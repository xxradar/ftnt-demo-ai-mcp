FROM xxradar/mcp-hackbot:latest

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir --break-system-packages -r requirements.txt

COPY mcp_server.py .

EXPOSE 8001

CMD ["python", "mcp_server.py"]
