# SnayManagerV2 updates

This public repository hosts SnayManager V2 update packages. The client checks GitHub Releases for a newer version when it starts.

## Update channel
Configure the installed SnayManager application with:
`nimunimunimurasion-sys/SnayManagerV2`

Updates are published as:
- `SnayManagerV2-update.zip` — versioned Python application source
- `SnayManagerV2-update.json` — version and SHA-256 integrity checksum

The launcher verifies the checksum before applying an update. Its existing local settings and browser profiles are not included in the update package.

**Important:** GitHub account credentials, Snay.io passwords, auth tokens, cookies, and browser profiles must not be committed here. Installing or updating does not guarantee simultaneous player connections; Snay.io server limitations remain in effect.

## Publication
The GitHub Actions workflow publishes or refreshes a release when update files change on `main`. Review updates before publishing.