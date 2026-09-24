# Sage Image Dependencies

Versioned, verified on-device image runtime assets for Sage.

This private repository stores separately downloadable image dependencies. Large binaries are attached to versioned GitHub Releases rather than committed into Git history or bundled in the app.

## WAI tiled decoder

Release asset: `wai-tiled-decoder-v1.zip` (experimental tiled Core ML VAE decoder for WAI Illustrious SDXL v17).

The app verifies the archive and each decoder file using the pinned SHA-256 manifest before installation. Source and licensing are included in the release package and this repository.

See [SOURCE.md](SOURCE.md), [LICENSE-FAIPL-1.0-SD.md](LICENSE-FAIPL-1.0-SD.md), and [Sage's conversion notes](https://github.com/AryaHub/Sage/blob/images-beta/docs/WAI_TILED_DECODER.md).

The repository is private for beta development. The in-app downloader cannot access private GitHub release assets without credentials; Sage will not embed a GitHub token. Make the asset/repository public before enabling unauthenticated in-app downloads for users.
