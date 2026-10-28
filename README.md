# CideKick releases

Builds of CideKick, which runs your GitHub Actions jobs on your own machine
and sends them back to GitHub's runners whenever that machine can't take them.

Download the latest from the [Releases](https://github.com/recondemon/cidekick-releases/releases/latest) page:

- **Windows:** `CideKick-Setup-<version>.exe`. Installs for your account only, with no administrator prompt.
  Remove it from Settings → Installed apps.
- **macOS:** `CideKick-<version>.dmg`, for Apple silicon.
- **Linux servers:** `cidekick-<version>-linux-<arch>.tar.gz`, the engine on its own.
  Run `cidekick install-agent` to keep it running under systemd.

Every release lists `SHA256SUMS`. Its notes say whether each build was signed.

This repository holds releases only; the source is private.