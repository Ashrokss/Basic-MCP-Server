# Build Your First MCP Server: Leave Management
This AI tool helps an HR with leave management related tasks. The codebase here is for MCP server that interacts with mock leave database and responds to MCP client queries

![image](https://github.com/user-attachments/assets/bb09b3cc-0110-4aff-a641-7f11a1174349)


# Setup steps
- Install Claude Desktop
- Install uv by running pip install uv
- Run uv init my-first-mcp-server to create a project directory
- Run uv add "mcp[cli]" to add mcp cli in your project
- Few folks may get type errors for which you can run pip install --upgrade typer to upgrade typer library to its latest version
- Write code in main.py for leave management server
- Install this server inside Claude desktop by running uv run mcp install main.py in the project directory
- Kill any running instance of Claude from Task Manager. Restart Claude Desktop
- In Claude desktop, now you will see tools from this server
