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
  <a href="https://gaiadesk.net/docs"><b>Docs</b></a> ·
  <a href="https://github.com/Gaia-Desk/gaiadesk-cli"><b>CLI</b></a> ·
  <a href="https://github.com/Gaia-Desk/gaiadesk-mcp"><b>MCP</b></a>
</p>

---

**GaiaDesk** is remote desktop software for remote access, remote support and
unattended access to your computers: an alternative to TeamViewer, AnyDesk and
RustDesk, with a command line, an MCP server and SDKs so scripts, CI pipelines
and AI agents can run commands, copy files and use the screen on the same
machines you reach by hand.

**Download:** [latest release](https://github.com/Gaia-Desk/gaiadesk-releases/releases/latest)
(macOS, Windows, Linux) · [gaiadesk.net/download](https://gaiadesk.net/download)

### What GaiaDesk does

- **Remote desktop that feels local.** Hardware HEVC over QUIC, forward error correction and adaptive bitrate keep the picture sharp and the input instant, even on rough Wi-Fi.
- **Reachable when you need it.** [Unattended access](https://gaiadesk.net/docs/unattended-access) survives reboots, sign-outs and updates.
- **More than a screen.** Terminal, file transfer, chat, clipboard, port forwarding and background jobs, on every platform.
- **Works without our servers.** LAN sessions run with no internet at all, and Mesh links your machines into a private network.
- **Built for teams.** SSO, roles, audit logs, [enterprise provisioning](https://gaiadesk.net/docs/enterprise-deployment) and branded clients.
- **Ready for AI agents.** Scoped, expiring [agent tokens](https://gaiadesk.net/docs/agent-access) that the desk enforces, with an audit log of everything an agent ran.

### Repositories

**App and command line**

| Repository | What it is | Get it |
|---|---|---|
| [**gaiadesk-releases**](https://github.com/Gaia-Desk/gaiadesk-releases) | Signed GaiaDesk app installers for macOS, Windows and Linux, plus QuickSupport and the CLI binaries | [Latest release](https://github.com/Gaia-Desk/gaiadesk-releases/releases/latest) |
| [**gaiadesk-cli**](https://github.com/Gaia-Desk/gaiadesk-cli) | The `gaiadesk` command line: exec, shell, copy files, background jobs, port forwarding, for scripts, CI and AI agents | [npm `@gaiadesk/cli`](https://www.npmjs.com/package/@gaiadesk/cli) |
| [**homebrew-tap**](https://github.com/Gaia-Desk/homebrew-tap) | Homebrew formula for the CLI on macOS and Linux | `brew install gaia-desk/tap/gaiadesk` |

**AI agents (MCP)**

| Repository | What it is | Get it |
|---|---|---|
| [**gaiadesk-mcp**](https://github.com/Gaia-Desk/gaiadesk-mcp) | Model Context Protocol server: let Claude, Cursor, VS Code and other AI agents run commands, move files and use the screen on your computers | [npm `@gaiadesk/mcp`](https://www.npmjs.com/package/@gaiadesk/mcp) |

**API SDKs** (the GaiaDesk Platform API, end-to-end encrypted desk operations)

| Repository | Language | Get it |
|---|---|---|
| [**gaiadesk-typescript**](https://github.com/Gaia-Desk/gaiadesk-typescript) | TypeScript / Node.js | [npm `@gaiadesk/sdk`](https://www.npmjs.com/package/@gaiadesk/sdk) · [`@gaiadesk/sdk-native`](https://www.npmjs.com/package/@gaiadesk/sdk-native) |
| [**gaiadesk-go**](https://github.com/Gaia-Desk/gaiadesk-go) | Go | [pkg.go.dev](https://pkg.go.dev/github.com/Gaia-Desk/gaiadesk-go) |
| [**gaiadesk-python**](https://github.com/Gaia-Desk/gaiadesk-python) | Python, sync and asyncio | [GitHub](https://github.com/Gaia-Desk/gaiadesk-python) |
| [**gaiadesk-java**](https://github.com/Gaia-Desk/gaiadesk-java) | Java / Kotlin | [GitHub](https://github.com/Gaia-Desk/gaiadesk-java) |
| [**gaiadesk-dotnet**](https://github.com/Gaia-Desk/gaiadesk-dotnet) | .NET (C#) | [GitHub](https://github.com/Gaia-Desk/gaiadesk-dotnet) |
| [**gaiadesk-ruby**](https://github.com/Gaia-Desk/gaiadesk-ruby) | Ruby | [GitHub](https://github.com/Gaia-Desk/gaiadesk-ruby) |
| [**gaiadesk-php**](https://github.com/Gaia-Desk/gaiadesk-php) | PHP | [GitHub](https://github.com/Gaia-Desk/gaiadesk-php) |
| [**gaiadesk-rust**](https://github.com/Gaia-Desk/gaiadesk-rust) | Rust | [GitHub](https://github.com/Gaia-Desk/gaiadesk-rust) |

**Embed SDKs** (a "Get help" button that shares your app's screen with your support team; see [Embedding GaiaDesk](https://gaiadesk.net/docs/embedding-gaiadesk))

| Repository | Platform | Get it |
|---|---|---|
| [**gaiadesk-embed**](https://github.com/Gaia-Desk/gaiadesk-embed) | Web apps (TypeScript, zero dependencies) | [npm `@gaiadesk/embed`](https://www.npmjs.com/package/@gaiadesk/embed) |
| [**gaiadesk-embed-electron**](https://github.com/Gaia-Desk/gaiadesk-embed-electron) | Electron and Node desktop apps | [npm `@gaiadesk/embed-native`](https://www.npmjs.com/package/@gaiadesk/embed-native) |
| [**gaiadesk-embed-swift**](https://github.com/Gaia-Desk/gaiadesk-embed-swift) | macOS apps (Swift Package) | [GitHub](https://github.com/Gaia-Desk/gaiadesk-embed-swift) |
| [**gaiadesk-embed-cpp**](https://github.com/Gaia-Desk/gaiadesk-embed-cpp) | C/C++ and Qt apps (CMake) | [GitHub](https://github.com/Gaia-Desk/gaiadesk-embed-cpp) |
| [**gaiadesk-embed-dotnet**](https://github.com/Gaia-Desk/gaiadesk-embed-dotnet) | Windows desktop apps (.NET 8) | [GitHub](https://github.com/Gaia-Desk/gaiadesk-embed-dotnet) |
| [**gaiadesk-embed-ios**](https://github.com/Gaia-Desk/gaiadesk-embed-ios) | iOS apps (Swift Package) | [GitHub](https://github.com/Gaia-Desk/gaiadesk-embed-ios) |
| [**gaiadesk-embed-android**](https://github.com/Gaia-Desk/gaiadesk-embed-android) | Android apps (Kotlin, AAR) | [GitHub](https://github.com/Gaia-Desk/gaiadesk-embed-android) |
| [**gaiadesk-embed-react-native**](https://github.com/Gaia-Desk/gaiadesk-embed-react-native) | React Native apps (iOS and Android) | [GitHub](https://github.com/Gaia-Desk/gaiadesk-embed-react-native) |
| [**gaiadesk-embed-flutter**](https://github.com/Gaia-Desk/gaiadesk-embed-flutter) | Flutter apps (iOS and Android) | [GitHub](https://github.com/Gaia-Desk/gaiadesk-embed-flutter) |

### Quick start

```sh
npm install -g @gaiadesk/cli        # or: brew install gaia-desk/tap/gaiadesk
gaiadesk login
gaiadesk devices
gaiadesk exec -d 123456789 -- uname -a
```

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

Docs: [Getting started](https://gaiadesk.net/docs/getting-started) ·
[The CLI for agents](https://gaiadesk.net/docs/cli-for-agents) ·
[Agent access](https://gaiadesk.net/docs/agent-access) ·
[Security](https://gaiadesk.net/docs/security)

### Get in touch

- **Help with the app:** [support@gaiadesk.net](mailto:support@gaiadesk.net)
- **Security reports:** [security@gaiadesk.net](mailto:security@gaiadesk.net) (please don't open public issues)
- **SDK, CLI or MCP bugs and ideas:** open an issue in the matching repository
