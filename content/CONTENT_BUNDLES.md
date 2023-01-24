# Content Bundles

### Format

Content bundles are served as `.tar` files that support the following compression formats based on their secondary file extension:

- `.tar.zst` -> `zstd` based compression (recommended)
- `.tar.gz` -> `gzip` based compression

All 3D Models **MUST** use the glTF file format with the `.gltf` file extension. As it is a very robust and complex file format, it is best to assume that features that are not supported unless support is explicitly specified in (TODO: add list of supported glTF features).

All shaders **MUST** use the SPIR-V format with the `.spv` file extension. This is needed for ensuring best cross-vendor and cross-platform graphical compatibility.

All scripts **MUST** use the webassembly module format with the `.wasm` file extension.

### Content Bundles Types

- [Worlds](./world/WORLDS.md)
- [Avatars](./avatar/AVATARS.md)
