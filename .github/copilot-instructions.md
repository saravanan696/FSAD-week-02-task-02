# Copilot instructions

## Project structure

- `EMC/saroo.html` is the current page entry point. The workspace is a standalone HTML scaffold; no application framework, scripts, stylesheets, or asset pipeline are present.
- The document already declares HTML5, English, UTF-8, and a responsive viewport. Preserve these document-level settings when editing the page.

## Build, test, and lint

- No build, test, or lint commands are defined in the current workspace.
- Preview the page by opening `EMC/saroo.html` directly in a browser.
- Playwright MCP is configured in `.vscode/mcp.json` for browser-based checks.

## Page conventions

- Keep page changes in the standalone HTML document unless the project gains a concrete need for separate assets or tooling.
- The current document title is `RESUME`; its body is empty, so do not assume any additional page content or behavior exists.
