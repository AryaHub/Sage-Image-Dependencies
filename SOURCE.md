# Source and provenance for the WAI tiled decoder

The compiled `VAEDecoder.mlmodelc` is a tiled Core ML conversion derived from the WAI Illustrious SDXL v17 VAE. It was generated from the reproducible source converter and pinned VAE fetcher in Sage:

- Converter: https://github.com/AryaHub/Sage/blob/images-beta/ImagePOC/Scripts/convert_wai_tile_decoder.py
- Pinned source fetcher: https://github.com/AryaHub/Sage/blob/images-beta/ImagePOC/Scripts/fetch_wai_vae_source.py
- Conversion scripts and dependency lock: https://github.com/AryaHub/Sage/tree/images-beta/ImagePOC/Scripts
- Pinned checkpoint source, revision and VAE hashes: https://github.com/AryaHub/Sage/blob/images-beta/docs/WAI_TILED_DECODER.md
- Original WAI model on Civitai.com: https://civitai.com/models/827184/wai-illustrious-sdxl?modelVersionId=2883731
- Upstream Core ML conversion repository: https://huggingface.co/LocalMuseAI/coreml-wai-illustrious-sdxl-v17-6bit
- Applicable license: [FAIPL 1.0-SD](LICENSE-FAIPL-1.0-SD.md); canonical text https://freedevproject.org/faipl-1.0-sd/

The package includes `wai-tile-manifest.json`, which pins the tested component file paths, sizes, SHA-256 hashes, and source revision used by the app importer.

These notices preserve source/provenance references; they are not legal advice and do not expand upstream rights or waive any upstream license terms.
