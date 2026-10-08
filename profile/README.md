<p align="center">
  <a href="https://gaiadesk.net">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Gaia-Desk/.github/main/profile/assets/lockup-dark-bg.svg">
      <img alt="GaiaDesk" src="https://raw.githubusercontent.com/Gaia-Desk/.github/main/profile/assets/lockup.svg" width="360">
    </picture>
  </a>
</p>

<h3 align="center">Any computer. Right here.</h3>

<p align="center">
  Fast, secure remote desktop for Mac, Windows and Linux,<br>
  with a terminal, file transfer and an API built for people <em>and</em> AI agents.
</p>

<p align="center">
  <a href="https://gaiadesk.net"><b>Website</b></a> ·
  <a href="https://gaiadesk.net/download"><b>Download</b></a> ·
  <a href="https://github.com/Gaia-Desk/gaiadesk-releases/releases/latest"><b>Releases</b></a> ·
  <a href="https://github.com/Gaia-Desk/gaiadesk-mcp"><b>MCP</b></a> ·
  <a href="https://github.com/Gaia-Desk/gaiadesk-typescript"><b>TypeScript SDK</b></a> ·
  <a href="https://github.com/Gaia-Desk/gaiadesk-python"><b>Python SDK</b></a>
</p>

---

### What GaiaDesk does

- **Remote desktop that feels local.** Hardware HEVC over QUIC, forward error correction and adaptive bitrate keep the picture sharp and the input instant, even on rough Wi-Fi.
- **Reachable when you need it.** Unattended access survives reboots, sign-outs and updates.
- **More than a screen.** Terminal, file transfer, chat, clipboard, port forwarding and background jobs, on every platform.
- **Works without our servers.** LAN sessions run with no internet at all, and Mesh links your machines into a private network.
- **Built for teams.** SSO, roles, audit logs, enterprise provisioning and branded clients.

### Build with GaiaDesk

| Repository | What it is | Install |
|---|---|---|
| [**gaiadesk-mcp**](https://github.com/Gaia-Desk/gaiadesk-mcp) | MCP server: let Claude, Cursor, VS Code and other AI agents run commands, move files and use the screen on your computers | `npx -y @gaiadesk/mcp` |
| [**gaiadesk-typescript**](https://github.com/Gaia-Desk/gaiadesk-typescript) | TypeScript SDK for Node.js | `npm install @gaiadesk/sdk` |
| [**gaiadesk-python**](https://github.com/Gaia-Desk/gaiadesk-python) | Python SDK, sync and asyncio | `pip install gaiadesk` |
| [**gaiadesk-cli**](https://github.com/Gaia-Desk/gaiadesk-cli) | The `gaiadesk` command line for scripts, CI and AI agents | `npm i -g @gaiadesk/cli` · `brew install gaia-desk/tap/gaiadesk` |
| [**gaiadesk-releases**](https://github.com/Gaia-Desk/gaiadesk-releases) | Signed builds of the GaiaDesk apps for every platform | [Download](https://gaiadesk.net/download) |

```ts
import { GaiaDesk } from "@gaiadesk/sdk";

const gd = new GaiaDesk();
const result = await gd.exec("123456789", "uname -a");
console.log(result.stdout);
```

```python
from gaiadesk import GaiaDesk

gd = GaiaDesk()
print(gd.exec("123456789", "uname -a").stdout)
```

### Get in touch

- **Help with the app:** [support@gaiadesk.net](mailto:support@gaiadesk.net)
- **Security reports:** [security@gaiadesk.net](mailto:security@gaiadesk.net) (please don't open public issues)
- **SDK or MCP bugs and ideas:** open an issue in the matching repository
