# HookshotBuilder Offline Edition

**A portable, self-contained Windows edition of the original Longshot/Hookshot Builder, adapted for offline use.**

HookshotBuilder Offline Edition is a modified version of the original Longshot/Hookshot Builder, adapted to provide a self-contained Windows experience.

The goal is simple: keep the Builder usable without depending on the original online infrastructure or requiring users to install and configure its build tools separately.

## Why this Offline Edition?

This project was born out of an unfortunate situation: the original Git repository was shut down without warning, leaving the Builder unusable due to its reliance on online resources and external dependencies.

The original project was **Hookshot by NotRexed**:
https://github.com/NotRexed/Hookshot

Rather than letting the application become unusable, I decided to adapt it and create **HookshotBuilder Offline Edition**.

My goal was to make the Builder fully portable and independent of the original online infrastructure, so users can keep using it without relying on external services, repository availability, or separate tool installations.

The result is a self-contained Windows edition, with the required build tools bundled locally and application data stored alongside the executable.

**This is my contribution: keeping the Builder usable by making it portable and 100% offline for regular builds.**

— Venomsrt10

## Features

- **Portable Windows application** — no traditional installation required.
- **Bundled build tools** — required tools are included locally.
- **Offline regular builds** — no dependency on the original online repository for normal builds.
- **Self-contained runtime** — .NET runtime is included.
- **Portable data storage** — settings and application data are stored alongside the executable.
- **Move-friendly** — the application folder can be moved to another location.
- **Original Builder workflow** — preserves the original build process and functionality.

## Requirements

- Windows 10/11, 64-bit.
- Sufficient free disk space for the application, bundled tools and generated build files.
- A valid game dump and any other files required by the original Builder workflow.

## Getting Started

1. Download the latest release.
2. Extract the complete archive to a folder of your choice.
3. Run `HookshotBuilder.exe`.
4. Configure your workspace and required input files.
5. Start your build.

**Important:** Keep the complete extracted folder structure intact. The application relies on its bundled `tools` directory.

## Offline Compatibility

Regular builds are designed to work offline using the bundled tools.

**DLSS builds are an exception:** enabling DLSS may require downloading the NVIDIA DLSS SDK and accepting its license, following the original workflow.

Therefore, the offline experience applies to regular builds when DLSS is disabled.

## Updates

The Builder's built-in update functionality has been disabled in this Offline Edition.

The original upstream repository is no longer available, so the original online update mechanism can no longer reliably retrieve the Builder or its updates. Disabling it also prevents users from being directed to a discontinued update source.

Updates to this Offline Edition, when available, will be published separately through this GitHub repository's Releases.

## Credits & Acknowledgements

This project is an adaptation of **Hookshot by NotRexed**:

- Original project: https://github.com/NotRexed/Hookshot
- Original author: NotRexed
- Offline adaptation: Venomsrt10

All original authors and contributors retain credit for their work. This edition focuses specifically on portability and offline usability.

This project is not affiliated with or endorsed by the original author.

## Licensing

The original project is distributed under the **GNU General Public License v3.0 or later (GPL-3.0-or-later)**.

This adaptation follows the applicable original project license. Third-party components bundled with the application remain subject to their respective licenses and terms.

Please refer to the included license and third-party notices for details.

## Disclaimer

This project does not include copyrighted games, game dumps, console keys, or other proprietary game content.

Users are responsible for providing their own legally obtained files and complying with the applicable licenses and terms of the included third-party components.

---

**HookshotBuilder Offline Edition**  
Maintained by **Venomsrt10**
