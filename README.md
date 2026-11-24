# Merch Maker connector (MCP)

[Merch Maker](https://merchmaker.ai) turns a sentence into custom merch: designs drawn with AI on real products, priced up front, then printed and delivered. This connector lets an AI assistant such as ChatGPT or Claude do that with you, inside the chat.

- **Server address:** `https://merchmaker.ai/mcp` (streamable HTTP, sign-in by OAuth)
- **Setup steps:** <https://merchmaker.ai/connect>
- **Support:** <https://merchmaker.ai/support> · hello@merchmaker.ai

## What it does

1. You say what you need, for example "forest green hoodies for our run club of 30, small logo on the chest".
2. Merch Maker suggests products it can make, and reads your brand from your website or a logo you upload.
3. It prepares design options on the real product, each with a price and sizes. You refine them in plain words.
4. You order for yourself or the team, or share a [group order](https://merchmaker.ai/group-orders) so each person picks a size.

Payment always happens on merchmaker.ai, never inside the assistant. It is a design tool for physical products, not an image generator.

## More

- [What Merch Maker is](https://merchmaker.ai/about)
- [Prices and minimums](https://merchmaker.ai/prices-and-minimums)
- [How it differs from other ways to make merch](https://merchmaker.ai/how-merch-maker-differs)
- [Designs by product](https://merchmaker.ai/custom)

`server.json` in this repository is the connector's manifest for the [MCP Registry](https://registry.modelcontextprotocol.io), name `ai.merchmaker/merchmaker`.

This repository holds the connector's public description only. The service itself is not open source.
