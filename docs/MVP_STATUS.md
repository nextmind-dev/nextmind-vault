# Private MVP status

NextMind Vault has a functioning private MVP for Windows 11. This page describes user-visible capability, not public availability or security certification.

## What currently works

### Files

The application provides a local workspace for importing, organizing, previewing, and exporting files and folders inside an encrypted vault. Operations remain explicit so the user controls when information enters or leaves the vault.

### Passwords and secrets

The application stores credential records, recovery codes, and other sensitive values in a dedicated workspace. It also provides password-generation and protected clipboard behavior intended for everyday local use.

### Notes

The application provides a separate workspace for private text notes, with the same local vault and session boundary as the other content.

### Storage formats

- **CryptoFS** is reused for the encrypted filesystem layer.
- **KDBX** is reused as the database format for passwords, secrets, and notes.

Using established components and formats reduces unnecessary custom cryptography, but it does not by itself make the whole application audited or suitable for every threat model.

## Current boundaries

- The application source code remains private.
- There is no public download, installer, executable, or supported release.
- The MVP has not completed an independent security audit.
- Public distribution is blocked pending third-party licensing resolution and the remaining security and release gates.
- Mobile applications are not part of the current MVP.

The current build is used only for private local development and owner testing. No public repository content should be interpreted as permission to obtain, test, redistribute, or reverse engineer a private application build.

See the [roadmap](../ROADMAP.md), [security policy](../SECURITY.md), and [distribution and source policy](../DISTRIBUTION.md) for the remaining gates.
