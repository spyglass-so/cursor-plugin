# Spyglass for Cursor

Competitive creative intelligence inside Cursor: discover brands and creators, research ads and organic content, and analyze hooks, campaigns, collaborations, landing pages, and public comments.

## Connect

This plugin connects to https://mcp.spyglass.so/mcp. Sign in to your Spyglass account through the OAuth flow when Cursor requests authentication. No API key is stored in this repository. Account access and usage limits follow your Spyglass plan.

The marketplace listing is pending submission. For local testing, copy this repository into `~/.cursor/plugins/local/spyglass`, reload Cursor, and confirm the two skills and Spyglass MCP server appear in Customize. Local plugin imports must be enabled for your organization. Complete OAuth, then try the prompts below.

## Try it

- Use Spyglass to find AG1's longest-running active Meta video ads and summarize their hooks.
- Use Spyglass to discover DTC hydration brands and compare their creative strategies.
- Use Spyglass to find K-beauty creators in the US with 20k–150k followers.

## Included

- **spyglass-accounts**: resolve brands and creators, discover competitors, and index missing accounts when authorized.
- **spyglass-media**: search creatives, retrieve account libraries, filter by taxonomy, and compare performance signals.
- **Hosted MCP server**: available tools are discovered from the live server. Follow its current schemas. Account indexing and feedback submission have side effects; use them only when the user requests or authorizes those actions. Do not include credentials or unrelated private information in feedback.

## Review and testing

Before submission, verify both skills load, complete OAuth in Cursor, and run a successful read-only Spyglass tool call. This repository does not claim that packaging checks alone verify the authenticated flow.

## Links

- [Spyglass](https://spyglass.so)
- [Documentation](https://docs.spyglass.so)
- [Privacy policy](https://spyglass.so/privacy)
- [Support](mailto:support@spyglass.so)

## License

MIT — see [LICENSE](LICENSE).
