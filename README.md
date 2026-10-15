# SHOPKIT plugins

SHOPKIT connects your own shop to ChatGPT or Claude. Inspect products and pages, prepare private drafts, and send proposed live changes to the owner for review in SHOPKIT Studio. Each owner signs in on their own shop and chooses permissions. Installing these files alone grants no access.

## Status

Version 0.1.1 is prepared for provider review. These packages are not yet approved or published in the ChatGPT or Claude directories. The hosted connection service is live, but a compatible, explicitly enrolled HTTPS shop is required. Real-account commissioning and a dedicated reviewer shop are still pending.

## Packages

- ChatGPT: [plugins/chatgpt](plugins/chatgpt), with the remote MCP server and workflow skill.
- Claude: [plugins/claude](plugins/claude). Use this folder as the plugin path when submitting this repository to the Claude developer portal.

[Connect with ChatGPT](https://shopkit-connect.vercel.app/plugins/chatgpt) · [Connect with Claude](https://shopkit-connect.vercel.app/plugins/claude)

## Access and boundaries

The service requires per-owner OAuth consent. Drafts stay unpublished. Live changes require an expiring owner review; the assistant cannot approve itself. Access can be revoked in Studio. The connector has no payment or refund tools. Appointment access needs separate permissions and the appointments plugin in the shop.

Never enter passwords, API keys, access tokens or customer data into GitHub issues. Send private support and security reports to info@kommon.io.

Published by Kommon.io Inc. [Support](https://shopkit-connect.vercel.app/support) · [Privacy](https://shopkit-connect.vercel.app/privacy) · [Terms](https://shopkit-connect.vercel.app/terms) · [How access works](https://shopkit-connect.vercel.app/security).
