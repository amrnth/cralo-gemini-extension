# Cralo for Gemini CLI

Cralo gives Gemini CLI direct access to pay-per-use tools for web search,
page extraction, transcription, public social data, and research. The extension
connects to Cralo's hosted MCP server and uses OAuth, so users do not need to
provide third-party provider API keys.

Successful paid calls consume prepaid Cralo credits. Current prices appear in
the individual tool descriptions. Credits are purchased and managed at
[cralo.ai](https://cralo.ai), outside Gemini CLI.

## Install

```sh
gemini extensions install https://github.com/amrnth/cralo-gemini-extension
```

Gemini CLI should open the Cralo OAuth flow when authentication is required. If
it does not, authenticate manually:

```text
/mcp auth cralo
```

## Links

- [Cralo](https://cralo.ai)
- [MCP documentation](https://cralo.ai/docs/mcp)
- [Privacy policy](https://cralo.ai/privacy)
- [Support](mailto:support@cralo.ai)
