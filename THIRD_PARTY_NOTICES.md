# Third-party components

Lodoka Code is derived from Team Room Community by Team Room Contributors (2026), distributed under MIT. The original copyright and permission notice remain in LICENSE.

Electron is distributed under MIT; its Chromium and other third-party notices are included in the desktop distribution. The separate Node.js runtime includes its LICENSE file. Desktop and web Lodoka L/chevron artwork is included under the repository MIT license.

The MIT license in this repository covers Lodoka Code source. It does not relicense external products.

- Claude Code and Codex are separate products. Their names identify compatible providers. Their CLIs are downloaded from official npm distributions only when the user requests installation in Lodoka; CLI binaries, subscriptions and credentials are not included in this repository. Each user signs in to their own account and remains subject to the provider's terms and limits.
- Manrope, Lora, Inter and JetBrains Mono font files are distributed under the SIL Open Font License. Full notices are retained beside the files in `public/fonts/`.
- JavaScript dependencies and their versions are listed in `package.json` and `package-lock.json`. Their own licenses remain applicable. No dependency directory is committed.
- The community window symbol is original artwork included under this repository's MIT license.
- This project is independently maintained; it is not an official application of either provider.

## Provider identification marks

ChatGPT/OpenAI Blossom is the property of OpenAI. The local vector paths are from OpenAI's official cookbook, revision 4a85c3018d20ceef48bf7549450c567896501bf9: examples/voice_solutions/realtime_translation_guide/livekit-translation-demo/public/brand/chatgpt-blossom-black.svg. Only empty margins were cropped through the SVG viewBox; the vector paths and proportions are preserved. See https://openai.com/brand/.

Claude is the property of Anthropic. The unmodified local mark was retrieved from https://claude.com/icon.svg on 2026-11-03. See https://www.anthropic.com/legal/trademark-guidelines. These small identification marks indicate supported providers; they do not imply endorsement or affiliation. Provider trademarks are not covered by this project's MIT license.

## Lucide icons

The local SVG interface icons are from https://github.com/lucide-icons/lucide (retrieved 2026-11-03). Lucide ISC/MIT license and contributor notices are preserved in desktop/assets/icons/LICENSE.

## Integration marks

Supabase, Vercel and GitHub identification marks are local Simple Icons SVGs, distributed under CC0. The notice is in public/assets/integrations/LICENSE.txt. Brand trademarks remain with their owners; no endorsement is implied. Additional Lucide vectors use the pinned upstream 0.577.0 tag and the included ISC/MIT notice in public/assets/LUCIDE-LICENSE.

Lodoka's Vercel companion plugin is original MIT code using documented read-only Vercel REST endpoints. It is distinct from Vercel's official OAuth MCP server. Unity CLI, Blender Lab MCP and community MCP bridges are installed separately and retain their own licenses.
## Optional editor components in 0.2.1

Blender Lab MCP 1.0.3 (GPL-3.0-or-later), its extension, uv 0.13.7 (MIT/Apache-2.0) and managed CPython (PSF license) are optional downloads, not bundled with the Lodoka installer. Official source/manifest/readme files remain in the separate component directory. Their licenses and upstream notices apply independently from Lodoka's MIT license. Unity CLI is obtained from Unity's official package; Unity's terms apply. Sources and pinned versions are documented in docs/INTEGRATIONS.md.

## Rich text and service automation (0.3.0)

The local rich-content bundle includes marked (MIT), DOMPurify (Apache-2.0 OR MPL-2.0), and highlight.js (BSD-3-Clause). Complete upstream license texts are distributed in public/vendor/licenses. The build uses esbuild (MIT). Browser service automation uses Playwright (Apache-2.0); its license is retained in the packaged dependency. Browser binaries are not bundled with Lodoka.

The Mixamo browser adapter is original Lodoka code. No source from the unlicensed third-party mixamo-mcp repository is redistributed. Adobe/Mixamo, Yandex and Google are independent services; their names identify integrations and do not imply endorsement. Source attribution for original Team Room Community and existing assets remains unchanged.

### T3 Code reference for Lodoka 0.5.0

The MIT-licensed pingdotgg/t3code repository was consulted for interface structure, orchestration, Git and portable-context patterns. The new Lodoka modules adapt those concepts to this project's existing implementation; no T3 runtime package is bundled. Keep the T3 MIT copyright/license notice with any future verbatim source extraction. Existing Team Room and bundled dependency notices remain applicable.

Development 0.6.0: `lib/native-checkpoints.mjs` adapts the paginated Codex history/revert boundary from T3 Code's `CodexThreadRevert.ts` and `CodexAdapterV2.ts` to Lodoka's transport. Copyright (c) 2026 T3 Tools Inc. The complete MIT license is retained in `public/assets/T3-CODE-LICENSE.txt` and is included with the application. This does not add the T3 runtime, cloud identity or updater.

## Lodoka icon 0.5.3

The application tile was supplied by the project owner. Its exterior background was removed with the image tool, preserving the supplied white ribbon and orange dot. The approved transparent PNG is retained as desktop/assets/icon-source.png; native sizes are packaged by scripts/prepare-icon.cjs. Existing Team Room copyright notices and unrelated third-party marks remain unchanged.

## Integration identification marks (0.5.4)

Unity tab/cube mark: unmodified PNG published by Unity on its branding page, downloaded from https://cdn.sanity.io/images/fuvbjjlp/production/2495ab2daae11fd3ed5d6b84477d513869f9a1b4-89x100.png . Usage reference: https://unity.com/legal/branding-trademarks . Lodoka Code is not sponsored by or affiliated with Unity Technologies or its affiliates. Unity and the Unity logo are trademarks or registered trademarks of Unity Technologies or its affiliates in the U.S. and elsewhere. The mark identifies the Unity integration in a secondary position; it is not Lodoka artwork.

Blender icon: unmodified PNG from https://download.blender.org/branding/square/blender_icon_256x256.png . The Blender logo is property of the Blender Foundation; see https://www.blender.org/about/logo/ . It identifies the Blender integration, not an affiliation or endorsement. These two identification assets are not covered by the CC0 license for the adjacent Simple Icons assets.

The file-code, text-wrap and person-standing interface glyphs are from Lucide's official repository (https://github.com/lucide-icons/lucide/tree/main/icons); the existing Lucide ISC license and Feather MIT attribution remain applicable.

## yaml 2.9.0

Native skill frontmatter uses yaml by Eemeli Aro, ISC. Full notice: public/assets/YAML-LICENSE-2.9.0.txt; the installed production dependency retains its LICENSE. The native inventory frontmatter/Claude precedence adaptation also preserves the existing T3 Tools Inc. MIT attribution above.
