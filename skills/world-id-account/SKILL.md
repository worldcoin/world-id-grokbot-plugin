---
name: world-id-account
description: Connect the user's World ID or check its connection status. Use for World ID sign-in, account, identifier, or verification-status requests.
---

# World ID Account

For browser tasks, open links in the user's default system browser and use
computer use to continue in that browser's existing profile. Reuse any tab
already opened by plugin authentication. Do not switch to an isolated browser profile for sign-in.
If you cannot control the user's browser, provide the link and instructions for
them to finish.

Call `get_world_id_account` to check status or begin connecting.
If sign-in is required, offer to connect; proceed if already requested:

- **Desktop/workspace plugin:** use native **Connect/Reconnect**. If you cannot
  activate it, point to the reconnect banner or plugin connection settings.
  Use these controls if the account tool is unavailable too. Do not substitute
  CLI login or claim the browser opened before it does.

After sign-in, check status again in the same chat.
If still unauthenticated or unavailable, report the connection as unconfirmed and ask the user to repeat their request in a new chat.
