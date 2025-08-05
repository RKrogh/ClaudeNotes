# Robert's Claude Notes

## MCP

### Context 7
Information library for LLMs.
context7.com
> claude mcp add --transcport http context7 https://mcp.context7.com/mcp

prompt:
> Analyze the codebase for any third-party APIs that are required or recommended (including the PLANNING.md and TASKS.md files). Make a plan to use the Context7 MCP to search relevant documentation needed for each of these APIs. Then, plan to add relevant documentation to a .md file in the /documentation folder of my project directory.

### Firecrawl
AI Web scraping. Better than Claude's built in (2025-08-05)
firecrawl.com
>  claude mcp add firecrawl -e FIRECRAWL_API_KEY=[your_api_key] -- npx -y firecrawl-mcp

### Playwright
Mimic UI moves.
https://playwright.dev/
https://github.com/microsoft/playwright-mcp
> claude mcp add playwright npx @playwright/mcp@latest
