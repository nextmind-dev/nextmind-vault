# NextMind Vault

**A privacy-first, offline encrypted vault for files, photos, documents, passwords and personal data. Built by Nico.**

> **In development — not available for download yet.**

NextMind Vault is a planned local digital vault designed to help people keep sensitive personal information under their own control. The first release is being designed for Windows 11, with Android and iOS considered for future versions.

## Vision

Personal data should not require a mandatory account, cloud service, or permanent internet connection. NextMind Vault is being designed around three principles:

- **Offline-first:** core vault operations are intended to work locally without an account or server.
- **Encrypted by design:** stored content and its sensitive metadata are intended to be protected using established cryptographic primitives and a reviewed, versioned vault format.
- **User control:** users should decide where their vault and backups are stored, when information is imported or exported, and how recovery material is kept.

No software can promise absolute security. NextMind Vault will document its threat model, limitations, recovery model, and audit status instead of relying on absolute or misleading security claims.

## Planned uses

NextMind Vault is intended to support:

- files and folders;
- photos and other personal media;
- documents;
- passwords and account details;
- recovery codes and other sensitive codes;
- private notes.

## Platforms

- **First platform:** Windows 11.
- **Future direction:** Android and iOS, after the storage format and cryptographic core have been validated.

## Project status

The project is currently in security architecture and core engineering work. There is no public application build and no supported download.

The application source code remains closed. This public repository is a product information and project-status repository; it is not an open-source release of the application. The application has not yet completed an independent security audit.

See [ROADMAP.md](ROADMAP.md) for planned milestones and [SECURITY.md](SECURITY.md) for responsible vulnerability reporting.

## Availability

When a verified Windows release is ready, the planned user experience is:

1. Download a signed Windows `.exe` installer from official GitHub Releases or a future official product website.
2. Install the application without developer tools.
3. Follow a short first-run guide.
4. Create a vault and save its recovery kit.
5. Continue to the main vault interface.

This distribution flow is planned for a later stage and is not currently available.

## Author

NextMind Vault is built by **Nico**.
