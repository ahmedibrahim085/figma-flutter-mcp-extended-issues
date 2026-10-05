# figma-flutter-mcp-extended: problem reports

This repository only collects problem reports for the `figma-flutter` MCP server (figma-flutter-mcp-extended). It holds no code; the server's source is kept in a separate private repository.

## Report a problem

[Open an issue](https://github.com/ahmedibrahim085/figma-flutter-mcp-extended-issues/issues/new/choose) and pick "Report a problem". The template asks for:

- the tool you called and its arguments;
- what the output showed, and what Figma shows;
- when it happened (UTC) and how often;
- the server version (`serverInfo.version` in the initialize result), the transport (stdio or HTTP), your client, OS and Node version;
- any workaround, and the impact.

Leave out Figma API keys, tokens, private file keys and project or client details. Redact file keys and node ids in arguments, for example `fileKey: <redacted>`.

The server's MCP `instructions` name this repository, so an agent can file the report for you.
