# Virgil release assets

This repository hosts versioned public download assets for the Virgil desktop
application. It contains installers, cryptographic checksums, provenance
records, and pinned model packages required during first-run setup.

Application source, client content, credentials, telemetry, and acceptance
evidence do not belong here.

Every release is tied to an exact Virgil application version. The application
verifies downloaded model files against SHA-256 pins before using them.
Downloading these assets does not send business data or inference requests to
an external service; Virgil runs inference locally.

Prereleases marked for qualification or release-candidate testing are not
approved production releases.
