# World ID for Grok Bot / Cursor

Connect your World ID. Check your verification status and find services and
benefits for verified humans.

## Use

Enable the World ID plugin in your host. Ask "What benefits are available with
World ID?" to browse published offers. Browsing benefits does not require signing in.

To connect, use the host's World ID MCP connection controls and complete browser
authorization. In Cursor, these controls are under **Customize**. Then ask
"Is my World ID verified?" to check your connection and verification. Ask
"Where can I find an Orb?" for the verification-location finder.

The plugin connects to the production service at `https://auth.world.org/mcp`.
It retains the Cursor public OAuth client and `world-id:read` scope. Account
access uses OAuth with your consent. Do not paste credentials or tokens into
chat. Each host manages its own connection.

The four included skills cover account connection, benefits, finding an Orb,
and browser sign-in. The plugin does not run a local server or install scripts.
Partners determine benefit eligibility and redemption. Connecting World ID does
not authorize purchases or connect partner accounts.

## Support and policies

- [World ID](https://world.org/world-id)
- [Support](https://support.world.org/hc/en-us/categories/38399542707219-World-ID)
- [Privacy policy](https://world.org/legal/privacy-notice)
- [Terms of service](https://world.org/legal/user-terms-and-conditions)
- [Source](https://github.com/worldcoin/world-id-grokbot-plugin)

Copyright (c) 2026 Tools for Humanity Corporation. Licensed under
[Apache-2.0 WITH LLVM-exception](LICENSE), without warranty.
