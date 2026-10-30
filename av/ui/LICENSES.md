# av/ui — UI chrome assets (wave 7 "Juice Kit" / Ink & Gold)

Served by the app as `av/ui/<file>` (the orchestrator copies this folder to `deploy/av/ui/`). Vetted from `_video_factory/assets_candidates/` (licenses verified 2026-10-29/30, see `assets_candidates/LICENSES.md`). Built 2026-10-29 by `mkassets.js` (headless-Chrome canvas → WebP); no file was hotlinked or downloaded for this step.

- **Fluent Emoji 3D** (Microsoft, MIT): 18 WebP files, 14 distinct objects — reward / hero moments only (ceremony hero + tiles, combo flame, mastery crown, badges, section marks).
- **Phosphor Icons** (MIT): 3 duotone SVGs — UI glyphs; the app inlines their path data, these files are the provenance record.
- Hand-drawn in the patch itself (no third-party source): the lock and map-pin glyphs, the "Perfect" stamp ring, the fly-to star sprite.
- Not used: the Fluent coin (bank-building face) — the token coin 🪙 stays as is for now; OpenMoji (CC BY-SA), game-icons (CC BY), Noto animated (CC BY + lottie runtime).

No visible credit is required by either license; the MIT notices below must ship with the files (this file ships with them). Suggested About-section line:

```
Fluent Emoji © Microsoft Corporation — MIT License (https://github.com/microsoft/fluentui-emoji)
Phosphor Icons © 2023 Phosphor Icons — MIT License (https://phosphoricons.com)
```

## Files (21, 63917 bytes before this notice)

| File | Bytes | Asset | Source | Format |
|---|---|---|---|---|
| hero-trophy-256.webp | 4840 | Fluent Emoji 3D "trophy" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 256×256 WebP (converted from the 256² PNG) |
| hero-star-256.webp | 6334 | Fluent Emoji 3D "glowing star" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 256×256 WebP (converted from the 256² PNG) |
| hero-books-256.webp | 2660 | Fluent Emoji 3D "books" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 256×256 WebP (converted from the 256² PNG) |
| hero-party-256.webp | 9634 | Fluent Emoji 3D "party popper" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 256×256 WebP (converted from the 256² PNG) |
| fire-96.webp | 2466 | Fluent Emoji 3D "fire" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| bullseye-96.webp | 3142 | Fluent Emoji 3D "bullseye" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| star-96.webp | 3172 | Fluent Emoji 3D "glowing star" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| crown-96.webp | 2950 | Fluent Emoji 3D "crown" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| sparkles-96.webp | 2944 | Fluent Emoji 3D "sparkles" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| ice-96.webp | 2262 | Fluent Emoji 3D "ice" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| compass-96.webp | 3264 | Fluent Emoji 3D "compass" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| rocket-96.webp | 2972 | Fluent Emoji 3D "rocket" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| gradcap-96.webp | 2440 | Fluent Emoji 3D "graduation cap" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| bulb-96.webp | 2434 | Fluent Emoji 3D "light bulb" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| books-96.webp | 1766 | Fluent Emoji 3D "books" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| trophy-96.webp | 2806 | Fluent Emoji 3D "trophy" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| party-96.webp | 4062 | Fluent Emoji 3D "party popper" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| gem-96.webp | 2206 | Fluent Emoji 3D "gem stone" | https://github.com/microsoft/fluentui-emoji/tree/main/assets | 96×96 WebP (converted from the 256² PNG) |
| ph-map-trifold-duotone.svg | 478 | Phosphor Icons "map-trifold-duotone" | https://github.com/phosphor-icons/core/tree/main/assets/duotone | SVG, verbatim (inlined into the app; file kept as provenance) |
| ph-fire-duotone.svg | 642 | Phosphor Icons "fire-duotone" | https://github.com/phosphor-icons/core/tree/main/assets/duotone | SVG, verbatim (inlined into the app; file kept as provenance) |
| ph-lightning-duotone.svg | 443 | Phosphor Icons "lightning-duotone" | https://github.com/phosphor-icons/core/tree/main/assets/duotone | SVG, verbatim (inlined into the app; file kept as provenance) |

## License texts

### Fluent Emoji

```
MIT License

Copyright (c) Microsoft Corporation.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Phosphor Icons

```
MIT License

Copyright (c) 2023 Phosphor Icons

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
