# Contributing to GaiaDesk

Thanks for helping make GaiaDesk better.

## Where things live

- **The GaiaDesk apps and servers** are closed source. To report a bug or ask for a feature in the apps, email [support@gaiadesk.net](mailto:support@gaiadesk.net). Please include your platform, app version (Settings → About) and what happened.
- **The SDKs and MCP server** ([gaiadesk-mcp](https://github.com/Gaia-Desk/gaiadesk-mcp), [gaiadesk-typescript](https://github.com/Gaia-Desk/gaiadesk-typescript), [gaiadesk-python](https://github.com/Gaia-Desk/gaiadesk-python)) are open source under the MIT licence, and contributions are welcome.

## Issues

- Search existing issues first.
- Use the issue templates, and include the SDK version, your OS and runtime version, and the `gaiadesk-cli --version` output.
- Remove tokens, passwords, access codes and desk IDs from anything you paste.
- Security problems go to [security@gaiadesk.net](mailto:security@gaiadesk.net), never to a public issue. See [SECURITY.md](SECURITY.md).

## Pull requests

1. For anything bigger than a small fix, open an issue first so we can agree on the approach.
2. Fork the repository and create a branch from `main`.
3. Keep changes focused, and write TypeScript (not JavaScript) in the TypeScript and MCP repositories.
4. Add or update tests, and make sure the repository's test command passes (`npm test`, or `python -m unittest` for Python).
5. Update the README and CHANGELOG when you change behaviour.
6. Open the pull request and fill in the template.

By contributing, you agree that your contributions are licensed under the repository's MIT licence.

## Code of conduct

Everyone taking part is expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
