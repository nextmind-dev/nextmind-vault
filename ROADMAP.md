# NextMind Vault Roadmap

This roadmap describes direction, not release commitments. Scope and ordering may change as security review and testing uncover new requirements.

## Phase 1 — Security and format foundation

- Define the threat model and security invariants.
- Specify the versioned, portable vault format.
- Build and test the independent cryptographic core using established primitives.
- Create known-answer, negative, compatibility, corruption, and recovery tests.
- Obtain independent review before freezing the first format version.

## Phase 2 — Local storage and recovery

- Implement crash-aware local storage for Windows 11 on NTFS.
- Add verified, copy-only import and explicit export.
- Implement recovery-kit creation, testing, and read-only recovery workflows.
- Exercise power-loss, corruption, disk-full, and partial-data recovery scenarios.

## Phase 3 — Windows application

- Build the Windows 11 desktop experience.
- Add files, photos, documents, password records, recovery codes, and notes.
- Add session locking, protected clipboard handling, diagnostics, and carefully restricted previews.
- Complete accessibility, installer, and clean-machine recovery testing.

## Phase 4 — Review and Windows distribution

- Complete independent cryptographic, format, recovery, and Windows application security assessments.
- Resolve or explicitly document findings.
- Produce a software bill of materials and third-party notices.
- Prepare a signed Windows `.exe` installer.
- Publish verified builds through official GitHub Releases or a future official product website.

The intended installation flow is:

1. The user downloads the official installer.
2. The application installs without requiring developer tools.
3. A first-run guide explains the local vault and its limitations.
4. The user creates a vault and saves a recovery kit.
5. The main vault interface opens after recovery confirmation.

## Phase 5 — Mobile investigation

- Validate the portable core and format on Android and iOS.
- Evaluate platform lifecycle, secure storage, file handling, backup expectations, and accessibility.
- Begin mobile product work only after the shared security model has passed the required review gates.

## Not currently available

NextMind Vault is in development and is not available for download. Features listed here must not be treated as implemented or audited until a release explicitly says so.
