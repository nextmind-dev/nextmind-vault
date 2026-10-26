# NextMind Vault

**A privacy-first, offline encrypted vault for personal files, passwords, secrets, and notes. Built by Nico.**

> **Private MVP in active development. There is no public download.**

NextMind Vault now has a functioning private MVP for Windows 11. It is designed for people who want sensitive personal information to remain under their own control, without a mandatory account, cloud service, or permanent internet connection.

The MVP is being validated privately. It is not a supported public release, its application source code remains private, and it has not completed an independent security audit.

## Current private MVP

The working Windows application currently provides three user-facing workspaces:

- **Files** — local encrypted storage and everyday file organization;
- **Passwords and secrets** — records for credentials, recovery codes, and other sensitive values;
- **Notes** — private text notes stored alongside the other vault content.

The MVP reuses established formats and components rather than inventing a new encryption format:

- **CryptoFS** provides the encrypted filesystem layer for files and vault metadata;
- **KDBX** provides an interoperable database format for passwords, secrets, and notes.

These are product-level format choices, not claims that NextMind Vault has been independently audited or approved for high-risk use. See [MVP status](docs/MVP_STATUS.md) for the current boundary.

## Product principles

- **Offline-first:** core vault operations work locally without an account or server.
- **Encrypted by design:** sensitive content is stored through established encrypted storage formats.
- **User control:** the user chooses the vault location, handles recovery material, and explicitly imports or exports information.
- **Honest security communication:** limitations, audit status, and release gates are documented without absolute security promises.

## Availability and source policy

There is no public build, installer, or supported download. The application and its source code remain private. This public repository contains product information, roadmap, security policy, and other public documentation only.

Public distribution is blocked until third-party licensing obligations, security review, release engineering, and signing requirements are resolved. See [Distribution and source policy](DISTRIBUTION.md).

## Project documents

- [Private MVP status](docs/MVP_STATUS.md)
- [Roadmap](ROADMAP.md)
- [Security policy](SECURITY.md)
- [Distribution and source policy](DISTRIBUTION.md)
- [Repository content license](LICENSE.md)

## Platforms

- **Current MVP:** Windows 11.
- **Future direction:** Android and iOS may be investigated only after the desktop security, format, licensing, and release gates are resolved.

## Author

NextMind Vault is built by **Nico**.
