# Notices

Codex Dream Skin Studio is an unofficial customization project and is not affiliated with, endorsed by, or sponsored by OpenAI.

## Software License

The custom non-commercial license in `LICENSE` applies to the software source code in this repository, including shell scripts, JavaScript modules, CSS, tests, and documentation.

Commercial use is not permitted in any form. Do not sell, sublicense, bundle into paid products, use in paid customer delivery, use in commercial consulting, use in agency work, use in a SaaS or enterprise workflow, or otherwise use this project for revenue-generating activity without separate written permission from the rights holder.

It does not grant rights to:

- OpenAI or Codex trademarks, product names, logos, or trade dress
- Official Codex or ChatGPT desktop application binaries
- `.app` bundles, `app.asar`, or any signed OpenAI application files
- User-supplied images or third-party artwork added by downstream users
- Character likenesses, franchise art, celebrity imagery, or copyrighted screenshots

## Bundled Assets

The public repository only includes abstract or project-owned demo assets. They are intended to demonstrate the theme system and can be replaced by the user.

Do not redistribute images that you do not own or have permission to share. Pull requests that add presets should use original, licensed, public-domain, or procedurally generated assets.

Bundled assets follow the same non-commercial restriction unless a file explicitly states a different license.

## Runtime

This project does not redistribute Node.js. At runtime it validates and uses the Node.js executable already signed and bundled inside the user's official Codex or ChatGPT desktop application.

## Security Model

Themes are applied through Chromium DevTools Protocol on loopback only. While a themed session is running, treat the local debugging port as sensitive and do not run untrusted local software that could attach to it.

Use the Restore launcher or `scripts/restore-dream-skin-macos.sh` to stop the injector and restore the original appearance.
