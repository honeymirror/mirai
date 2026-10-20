# Mirai RenderDragonShaderLoader Variant

This repository is a fork of [bambosan/mirai](https://github.com/bambosan/mirai).
The `rdloader-variant` branch contains an unofficial compatibility variant for
RenderDragonShaderLoader.

## Upstream

- Original project: [bambosan/mirai](https://github.com/bambosan/mirai)
- Original author: bambosan
- Upstream version used for this variant: Mirai 3.0.0
- Original license: MIT, preserved in [LICENSE](LICENSE)

This variant is not published, endorsed, or supported by the original author as an official
Mirai release.

## What This Variant Changes

- Adds RenderDragonShaderLoader pack metadata (`options.json`, `rdloader.pack.json`,
  `variants.json`, and `shaders.properties`).
- Adds localized parameter names under `lang/`.
- Exposes selected Mirai controls through RenderDragonShaderLoader runtime uniforms.
- Provides precompiled Windows material outputs so players do not need to compile the pack
  on first use.

The `rdloader-variant` branch is the complete importable pack. It includes source, metadata,
localization, and precompiled materials directly in the repository, so GitHub's generated
code ZIP can be imported without a separate release asset.

## Compatibility

- Target game: Minecraft Bedrock 1.26.51
- Required mod: RenderDragonShaderLoader 0.2.0-beta or later
- Backend used for the precompiled pack: albite / Direct3D_SM65

## Installation

1. Install RenderDragonShaderLoader.
2. Open the repository's `rdloader-variant` branch.
3. Click **Code > Download ZIP**.
4. Import the downloaded ZIP into the mod.
5. Select the `Default` configuration and apply it.

The repository package already contains compiled materials. A normal installation should not need
to run the shader compiler again.

## Licensing and Redistribution

Mirai remains copyright (c) 2026 bambosan and is distributed under the MIT License. A copy of
the upstream license is included in the repository beside this notice.

The RenderDragonShaderLoader compatibility metadata and packaging changes are provided under
the same MIT terms unless a file states otherwise.
