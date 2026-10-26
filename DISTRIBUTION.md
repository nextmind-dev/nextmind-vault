# Distribution and source policy

## Current publication boundary

NextMind Vault is a closed-source application in private development. This public repository is limited to product-facing documentation. It does not contain or license the application source code, tests, build configuration, internal specifications, executable files, vault data, KDBX databases, or brand assets.

There is no official public executable, installer, archive, or supported download. Any future distribution requires a separate owner decision and must not be inferred from the existence of this repository or the working private MVP.

## Distribution gate

Public distribution remains blocked until all applicable obligations and release risks have been resolved for the exact build, including:

- GPL, AGPL, commercial-license, attribution, notice, and redistribution requirements;
- a complete software bill of materials and third-party notices;
- removal, replacement, relicensing, or properly authorized use of components incompatible with the intended closed-source distribution model;
- security, recovery, accessibility, and clean-machine validation;
- code signing, provenance, release-channel, and update procedures;
- explicit owner approval for the selected artifact and publication channel.

Documentation of a dependency or format does not imply that its license permits a closed-source binary distribution. No executable will be published while that question remains unresolved.

## Source and artifact policy

- The application source code remains private.
- Private design documents, implementation details, tests, configuration, and internal specifications remain private.
- User data, vault metadata, recovery material, credentials, and KDBX files must never be published.
- Application executables and installers must not be attached to this repository or its releases without explicit approval after all gates are satisfied.
- Public documentation must describe user-visible behavior without exposing sensitive implementation details.

The repository's documentation license is stated in [LICENSE.md](LICENSE.md). Third-party projects retain their own licenses and trademarks.
