# NextMind Vault Roadmap

This roadmap separates the working private MVP from future release work. It describes direction, not release commitments, and does not announce a public build.

## Working private MVP

- A Windows 11 desktop application with **Files**, **Passwords and secrets**, and **Notes** workspaces.
- Local encrypted file storage using CryptoFS.
- KDBX-based storage for passwords, secrets, and notes.
- Explicit local import and export workflows.
- Session locking, protected clipboard behavior, local owner testing, and automated application tests.

These capabilities are implemented in private code. They have not completed independent security assessment and are not publicly distributed.

## Before any public distribution

- Resolve all third-party GPL, AGPL, commercial-license, notice, and redistribution obligations while keeping the application source closed.
- Produce a complete software bill of materials and third-party notices for the exact release build.
- Complete threat-model, storage, recovery, dependency, and Windows application security reviews.
- Expand corruption, disk-full, interrupted-write, recovery, and clean-machine testing.
- Complete accessibility and usability review.
- Establish reproducible release engineering, signing, provenance, and update procedures.
- Prepare and test an installer only after the licensing and security gates are satisfied.
- Publish a release only through an explicitly approved official channel.

No date is committed for these gates, and passing one gate does not imply that the others are complete.

## Later product work

- Refine diagnostics, recovery guidance, restricted previews, and operational hardening.
- Validate portability and interoperability against supported CryptoFS and KDBX versions.
- Investigate Android and iOS only after the desktop security, format, licensing, and release gates are resolved.

## Not currently available

There is no public source release, executable, installer, or supported download. The public repository contains documentation only. See the [private MVP status](docs/MVP_STATUS.md) and [distribution policy](DISTRIBUTION.md).
