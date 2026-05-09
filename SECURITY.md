# Security Notes

## Download Safety

Download Codex Profile Switcher only from this repository's GitHub Releases page:

[https://github.com/qasimkhosa/Codex-Profile-Switcher/releases/latest](https://github.com/qasimkhosa/Codex-Profile-Switcher/releases/latest)

Verify the SHA256 hash shown in the release notes before running the app.

## Sensitive Local Files

Codex profile folders can contain local login state. Do not upload, share, or email:

- `auth.json`
- profile folders
- local logs that include account details
- license keys

## Reporting Security Issues

Do not open a public GitHub issue for sensitive security reports. Email:

[admin@bitnyxt.com](mailto:admin@bitnyxt.com)

Include enough detail to reproduce the issue, but do not include private tokens or credentials.

## Obfuscation

Release builds are obfuscated with Obfuscar to make casual decompilation and modification harder. Obfuscation is not a guarantee against reverse engineering.
